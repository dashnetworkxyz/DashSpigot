# DashSpigot [![Build](https://jenkins.dashnetwork.xyz/job/DashSpigot/badge/icon)](https://jenkins.dashnetwork.xyz/job/DashSpigot/)
Fork of [DashSpigot](https://github.com/dashnetworkxyz/DashSpigot) 1.8.8 focused on bug fixes and API backports.

See a full list of patches [here](./patches/dashspigot/).

## Using
You can download the latest pre-built server JAR by clicking the download button below.  
[![Download](https://custom-icon-badges.demolab.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white)](https://jenkins.dashnetwork.xyz/job/DashSpigot/lastSuccessfulBuild/artifact/paperclip.jar)

## Building
To compile DashSpigot, you'll need:
- JDK 8 (or above)
- Git
- Bash

Building, patching, and compiling are all done through the main `dash` script.

DashSpigot can be built by running `./dash jar`, and you will find the final Paperclip jar in `paperclip.jar`
