# DashSpigot [![Build](https://jenkins.dashnetwork.xyz/job/DashSpigot/badge/icon)](https://jenkins.dashnetwork.xyz/job/DashSpigot/)
Fork of [PandaSpigot](https://github.com/hpfxd/PandaSpigot) 1.8.8 focused on bug fixes and API backports.

See a full list of patches [here](./patches/dashspigot/).

## Using
You can download the latest pre-built server JAR by clicking the download button below.  
[![Download](https://custom-icon-badges.demolab.com/badge/-Download-blue?style=for-the-badge&logo=download&logoColor=white)](https://jenkins.dashnetwork.xyz/job/DashSpigot/lastSuccessfulBuild/artifact/paperclip.jar)

## API
<details>
<summary>Maven</summary>

```xml
<repositories>
    <repository>
        <id>dashnetwork-repo</id>
        <url>https://nexus.dashnetwork.xyz/repository/maven-snapshots/</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>xyz.dashnetwork.dashspigot</groupId>
        <artifactId>dashspigot-api</artifactId>
        <version>1.8.8-R0.1-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
</dependencies>
```
</details>


<details>
<summary>Gradle (kts)</summary>

```kotlin
repositories {
    mavenCentral()
    maven(url = "https://nexus.dashnetwork.xyz/repository/maven-snapshots/")
}

dependencies {
    compileOnly("xyz.dashnetwork.dashspigot:dashspigot-api:1.8.8-R0.1-SNAPSHOT")
}
```
</details>

## Building
To compile DashSpigot, you'll need:
- JDK 8 (or above)
- Git
- Bash

Building, patching, and compiling are all done through the main `dash` script.

DashSpigot can be built by running `./dash jar`, and you will find the final Paperclip jar in `paperclip.jar`
