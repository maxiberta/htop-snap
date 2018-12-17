<h1 align="center">
  <a href="https://hisham.hm/htop/">
    <img src="https://hisham.hm/htop/htop-logo.png" alt="htop">
    <br />
    htop
  </a>
</h1>

<p align="center">
  <b>This is the snap for <a href="https://github.com/hishamhm/htop">htop</a></b>, <i>an interactive process viewer</i>. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.
</p>

<p align="center">
  <a href="https://snapcraft.io/htop"><img src="https://raw.githubusercontent.com/snapcore/snap-store-badges/master/EN/%5BEN%5D-snap-store-black.png" alt="Get it from the Snap Store"></a>
</p>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

## Command-line Installation

    sudo snap install htop

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

That'll install the latest _stable_ release of `htop`.

If you want the _next point release_ of `htop`, install from the `beta` channel instead:

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

| [maxiberta](https://github.com/maxiberta/) |

## Upstream

| [hishamhm](https://github.com/hishamhm) |
