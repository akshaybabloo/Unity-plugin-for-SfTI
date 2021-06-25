# Unity plugin for SfTI

Unity plugin for SfTI project for identifying Valence and Arousal

## Introduction

there are two parts to this project - `example` and `plugin`. `example` is a simple 2D game built in Unity that imports the plugin. `plugin` is a managed code that listens for UDP packets from [DataLogger](https://github.com/akshaybabloo/DataLogger).

## Requirements

Following are the requirements:

1. Unity 2020 LTS
   1. On windows it uses .Net Framework 4
   2. On macOS it uses mono (should usually install with the Unity engine)
   3. Plugin can run on any version of the Unity engine but its been tested on the 2020 LTS version
2. Visual Studio 2019 Enterprise (only Windows) or JetBrains Rider (Windows or macOS)
3. [DataLogger](https://github.com/akshaybabloo/DataLogger)

## Running the Game

TODO