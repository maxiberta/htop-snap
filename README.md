# htop-snap
The [`htop`](https://github.com/hishamhm/htop) utility packaged as a [snap](https://snapcraft.io/).

Once installed, this snap needs manually connecting to some plugs:
```
sudo snap connect htop:mount-observe
sudo snap connect htop:process-control
sudo snap connect htop:system-observe
```
