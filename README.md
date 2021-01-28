<p align="center">
  <b>This is the snap for <a href="https://htop.dev/">htop</a></b>, <i>an interactive process viewer</i>.
  <br/>
  It works on Ubuntu, Fedora, Debian, and other major Linux distributions.
</p>

<p align="center">
  <a href="https://snapcraft.io/htop">
    <img alt="htop" src="https://snapcraft.io/htop/badge.svg" />
  </a>
</p>

## Command-line Installation

    sudo snap install htop

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

That'll install the latest _stable_ release of `htop`.

Or, if you're feeling adventurous, try the autobuilds for the _next major release_ from the `edge` channel:

    sudo snap install htop --edge

## Permissions (optional)

Once installed, this snap can optionally be connected to some extra plugs:

    sudo snap connect htop:mount-observe
    sudo snap connect htop:network-control  # DELAYACCT support

## The Snapcrafters

[maxiberta](https://github.com/maxiberta/)

## Upstream

[htop-dev](https://github.com/htop-dev/htop)
