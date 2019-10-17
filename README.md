# The Best Game Ever
This repository contains the source code for our game that we are planning on making for Hacktober 2019! :ghost:

> The documentation will be a heavy WIP!

## How To Configure Unity to work with GitHub
For a quick and nice overview, I recommend watching [this](https://www.youtube.com/watch?v=qpXxcvS-g3g) video!

1. Make sure you have __Unity 2019.2.8f1__ installed. For instructions on how to get this, download __Unity Hub__ from [here](https://store.unity.com/).
  - The Free Unity version will do
2. When Unity Hub is downloaded, install the specific version that is mentioned above under the __Installs__ sidebar.
3. Clone this repo to your computer and open Unity Hub and import in this project into it.

:tada: You did it, now your project can be opened in Unity Hub! This is where you go when you need to work on the project.

## General Rules for Working on the project
1. __Make__ sure you pull down for any new changes from `master` by doing `git pull --rebase origin master`
2. All work should be done in a feature branch eg. `ms/issue-1`
3. __ONLY__ push/commit your work when Unity is not open.

## Project Hierarchy
- `Assets`: Where all of the Unity Resources are in (DO NOT remove from this!)
     - `_Game`
          - `Scripts`: All of the scripts that are written for the game are located in here. (WIP, may include sub directories based on functionality)
          - `Scenes`: All of the levels that have been made out for the game are located here. This includes all terrain and pathfinding objects.
          - `Sounds`:
               - `BGM`: All of the background music will be here
               - `SFX`: All of the sound effects will be here
          - `Prefabs`: All of the templated GameObjects will be in here. (WIP, may include sub directories based on functionality)
          - `Graphics`:
               - `Sprites`: All of the 2D Art will be in here
               - `Textures`: All of the textures will be in here
               - `UI`: All of the user interface art will be here
