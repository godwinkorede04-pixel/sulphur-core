# Sulphur

## Introduction
### Learning Objectives
At the end of this documentation, you should know the following:
* What Sulphur is all about.
* The features of the Sulphur Library.
* The planned features of the Sulphur Library.
 
### Target Audience
This documentation is aimed at the following audiences:
* Doom Developers
* Speedrunners

### Definition of Terms
**Sulphur** is a library for creating **instanced GZDoom launchers**.
**A GZDoom launcher** is a tool(either a program or script) that lets users organize, manage, and launch various mods and configuration setups for the GZDoom source port of classic Doom games.
**UNIX Systems** are a family of multitasking, multi-user operating systems known for their flexibility, robustness and use in servers, workstations and modern devices.Examples are MacOS and Linux.


All files saved by Sulphur are stored under a `sulphur` directory to ensure instances are easily transferrable between implementations.
> ⚠ It currently compiles only on **UNIX systems** die to its use of the `xdg` crate. 

---

## Features of Sulphur
The following are the features Sulphur allows you to access:

* Create new instances
* Track playtime
* Sort instances by playtime or last played
* Delete instances
* Add/remove Mods and IWADs, and optionally move them into the shared `sulphur` data folder
* Create and import `.brimpkg` files (ZIP archives in a trenchcoat containing instances)
* Instance-specific save folders
* Support for additional parameters per instance
* Change the command used to run GZDoom (helpful for custom paths or Flatpak installations of GZDoom)

---

## Planned Features
The following are the planned features to Sulphur:

* Documentation
* Global additional parameters

## Summary
Sulphur allows developers to create self contained GZDoom launchers where each mod setup is kept seperate and organised.
It can only be compiled on UNIX Systems.


