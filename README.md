-<p align="center">
<a href="https://discord.gg/jEtwguzZ4R"><img alt="" src="https://img.shields.io/badge/Discord-Channel-blue" height="20"/></a>
<a href="https://www.youtube.com/@YourTradeMaster"><img alt="" src="https://img.shields.io/badge/Youtube-Channel-db2e73" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/commit-activity/t/drkhodakarami/JiReference" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/last-commit/drkhodakarami/JiReference" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/downloads/drkhodakarami/JiReference/total" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/license/drkhodakarami/JiReference" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/badge/Maintained-YES-31ad31" height="20"/></a>
	</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#thelibrary)

## ➤ What is this library?

This is a simple yet useful library for adding a reference class that has helper methods for creating tags, and will carry the mod id of your mod. 
In your main mod, you will extend this class, replace the ModID attribute with your mod id one, and then you can add anything you need to the inherited class.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#dependency)

## ➤ Depending Your Mod

This library is using repsy for maven publishing system. Follow the guideline bellow to make dependency for your mod.
This library is depending on JiLogger Library so you should add it to your main mod too.

### ➤ Latest Version: 1.0.0

First you need to add the maven to your `build.gradle` repositories:

```Maven Repository
repositories 
{
	mavenCentral()
    maven { url 'https://repo.repsy.io/mvn/jiraiyah/jilibs' }
}
```

then you need to add the dependency into your dependency section in `build.gradle`

```dependencies
dependencies 
{
    modImplementation include("jiraiyah.logger:jilogger:${jilogger_version}")
    modImplementation include("jiraiyah.reference:jireference:${jireference_version}")
}
```

Finally, we need to add an entry inside `gradle.properties` using the version from the maven repository. The version should look like x.x.x-MCx.x.
x for sub versions of Minecraft, and for the main versions of the game it should be like x.x.x-MCx.x

Look into [MAVEN REPOSITORY](https://repo.repsy.io/mvn/jiraiyah/jilibs/jiraiyah/reference/) for the proper versioning.
Look into [JiLogger REPOSITORY](https://repo.repsy.io/mvn/jiraiyah/jilibs/jiraiyah/logger/) for the proper versioning.

```gradle.properties
jireference_version=x.x.x
jilogger_version=y.y.y
```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#contributors)

## ➤ Contributors

| [<img alt="Alireza Khodakarami" src="https://avatars.githubusercontent.com/u/77685668?v=4" width="100">](https://www.youtube.com/@YourTradeMaster) |
|:--------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                          [Alireza Khodakarami](https://www.youtube.com/@YourTradeMaster)                                           |
|                                          [khodakarami_dr@outlook.com](mailto:khodakarami_dr@outlook.com)                                           |
|                                                                        🔥🔧                                                                        |

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#license)

## ➤ License

Licensed under [MIT](https://opensource.org/licenses/MIT).

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#table-of-contents)

## ➤ Table of Contents

* [➤ The Library Info](#-thelibrary)
* [➤ Depending to Library](#-dependency)
* [➤ Contributors](#-contributors)
* [➤ License](#-license)