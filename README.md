<h1 align="center">
  <img src="https://hisham.hm/htop/htop-logo.png" alt="htop">
  <br />
  htop
</h1>

<p align="center"><b>This is the snap for `htop`</b>, <i>an interactive process viewer</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

## Install

    sudo snap install htop

That'll install the latest _stable_ release of `htop`.

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

If you want the _next point release_, install from the `beta` channel instead:

    sudo snap install htop --beta

Or, if you're feeling adventurous, try the _next major release_ from the `edge` channel:

    sudo snap install htop --edge

## Permissions

Once installed, this snap needs manually connecting to some plugs:

    sudo snap connect htop:mount-observe
    sudo snap connect htop:network-control  # optional, for DELAYACCT support
    sudo snap connect htop:process-control
    sudo snap connect htop:system-observe


![htop](https://hisham.hm/htop/htop_graph.gif "htop")

## The Snapcrafters

| [![maxiberta](https://avatars2.githubusercontent.com/u/381336?s=128&v=4)](https://github.com/maxiberta/) |
| :---: |
| [maxiberta](https://github.com/maxiberta/) |

## Upstream

| [![hishamhm](https://avatars3.githubusercontent.com/u/245621?s=128&v=4)](https://github.com/hishamhm) |
| :---: |
| [hishamhm](https://github.com/hishamhm) |
