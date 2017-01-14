# Manifest
Manifests for cloning creator repositories. Generally not needed to develop or
build any of the creator projects however useful to developers who are working
on all parts of the creator projects. This tool allows you to efficiently
manage differences across many repos, see 
https://source.android.com/source/using-repo.html.

You can do everything without using these manifests so don't worry about them
if you don't need to.

#### Steps for cloning could be:
- mkdir creator-projects && cd creator-projects
- repo init -u https://github.com/CreatorKit/manifest.git
- repo sync

After above steps, your directory structure would be like:
```
creator-projects
|
+--tools
|    +--creator-docker
+--dist
|    +--openwrt
|    +--openwrt-feeds
|        +--packages
|        +--Ci40-platform-feed
|        +--Creator-feed
|    +--contiki
+--packages
     +--... (all the apps/libs we work on)
```
