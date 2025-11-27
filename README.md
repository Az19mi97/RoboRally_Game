# Project - RoboRally-Project

RoboRally is a board game where players control programmable robots racing across a hazardous factory floor. Each player programs a sequence of movement cards to navigate their robot toward checkpoints while avoiding obstacles, conveyor belts, and other players’ robots. The goal is to reach all checkpoints in order as quickly as possible, using strategy and planning.

## Project Origin and Context
- Project retrieved from my GitHub account created with my student email, due to loss of access.
- Originally completed as part of the course during the 4th semester in 2023.
- Re-uploaded to this GitHub repository for reference and portfolio purposes.

## How to run the Application (Through IntelliJ)
1. First of all, open the IDE and replace the files with your empty Maven project.
2. Secondly, download [JavaFX](https://gluonhq.com/products/javafx/) and set it up. The software uses JavaFX UI framework. If you have problem with building the software and maven’s JavaFX installation, here you can find detailed information how to install it manually and setup the project properly, by following this tutorial: [HowToJavaFX](https://openjfx.io/openjfx-docs/#IDE-Intellij).
3. Start the program in the class `StartRoboRally`, this class will start the program. Remember to follow the tutorial properly, at the end you'll have to add VM Options.
4. Click 'file', and then 'New Game'.
5. Choose amount of players.
6. You're ready to play.


## Current Features:
- FileLoader - Extension to load a json file.
- InterfaceAdapter - Converts to GSON.
- 'Left or Right' is now working properly.
- Antenna - Still in progress.
- Others will move when landing (pushing) on another's space.
- Wall - You won't be able to walk through walls.
- FieldAction:
    - CheckPoints.
    - Conveyor Belt.
    - Gear.
    - Pit.
