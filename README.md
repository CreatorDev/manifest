# Manifest

Manifest for cloning creator kit repositories.

#### Steps for cloning could be:
- mkdir local_dir_name
- cd local_dir_name
- repo init -u https://github.com/CreatorKit/manifest.git -b branch_name
- repo sync

After above steps, your directory structure looks like:
```
.
├── build
├── constrained-os
│   └── contiki
├── dist
│   ├── openwrt
│   ├── openwrt-img-feeds
│   └── openwrt-pkg-feeds
├── docs
│   └── creator_docs
└── packages
    ├── AwaLWM2M
    ├── button-sensor
    ├── led-actuator
    └── libobjects
```
