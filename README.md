# Introduction

Mac OS X Catalina can only use 64-bit applications now. Unfortunately, it became incompatible with UMM which still requires some 32-bit code to work properly. This repo presents a temporary solution to use mods with Pathfinder:WoTR on a Mac.

# How

I have both Windows and Mac. All I did was install UMM on Windows following the documentation and then prepared the ZIP on this repo with the changed assets from that installation.

# Instructions

## GOG

1. Create a folder */Applications/Mods*. This is where you will have to manually unzip any mod you are considering to use.

2. Backup */Applications/Pathfinder Second Adventure/Contents/Resources/Data/Managed/UnityEngine.UIModule.dll*.

3. Download ZIP file from this repo and copy extracted contents into */Applications/Pathfinder Second Adventure/Contents/Resources/Data/Managed*.

## Steam

1. Create a folder */Users//Library/Application Support/Steam/steamapps/common/Pathfinder Second Adventure/Mods*. This is where you will have to manually unzip any mod you are considering to use.

2. Backup */Applications/Pathfinder Second Adventure/Contents/Resources/Data/Managed/UnityEngine.UIModule.dll*.

3. Download ZIP file from this repo and copy extracted contents into */Users//Library/Application Support/Steam/steamapps/common/Pathfinder Second Adventure/Wrath.app/Contents/Resources/Data/Managed*

TESTED WITH Pathfinder:WoTR 1.0.1x only.