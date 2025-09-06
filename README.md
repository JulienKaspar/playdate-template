## General

This is a template that I used with some friends for the PlayJam4 and PlayJam5 to develop small Playdate games.
Hopefully this can be build on more but the basics are all here.

## Clone the Repo

Step 0 of the process. More info:
https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository#cloning-a-repository

## Dev Setup

Either **manually** run the `pdc` compiler and the simulator, or use **VSCode** as interface for git, code and launching the simulator.

### Download the PlaydateSDK

Download the **Software Development Kit**. It's basically the game engine.
https://play.date/dev/

It has most of what we need, including a Playdate Simulator to play the game directly on the computer.

On Windows it's an install .exe. For Linux it's a .zip.
Either way, choose a folder somewhere where it's easy to find and hard to accidentally delete or move.

IMPORTANT: The .exe not actually installing it as a software. So it cannot be easily found via search as a program.

### Setup VSCode

It's ideal to use VS Code because of some handy extensions that will make your life a LOT easier.

#### Install the VS Code Extensions
- Playdate from Orta
- Playdate Debug from midouest
- Lua from sumneko

#### Vital Settings
To compile the game, the computer or VS Code needs to know where the SDK can be found.
There are a few ways to do this, both locally and global, but the easiest is the following:

1. Click on the Settings button at the bottom left (gear icon)
2. Click on "Settings"
3. Type "Playdate" into the search field
4. Under "Extensions" in both "Playdate" and "Playdate Debug" you'll find the "SDK path" setting.
5. Go to a file browser find the Playdate SDK folder you from earlier and copy the path to it.
6. Paste the path into each of the two "SDK path" settings.

### Play the Game

With everything set up, here's how you do.

#### From VS Code

Simply press F5 or press the play button at the top right of the window.
This will compile the game and launch it via the Playdate Simulator.
With Shift F5  you can close the Simulator again.
The compiled game .pdx will be put into a folder like "builds" or "output" in the root of the project.

#### Use the Playdate as a Controller

If the device is connected via cable and not locked, you can use it as a controller.
In the Simulator menus click on:
Device → Use Device as Controller

#### Put the Game on the Playdate

Device → Upload Game to Device
 
