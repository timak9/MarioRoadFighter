# ROAD FIGHTER - Final Project

This project is a digital design implementation of the classic arcade game *Road Fighter*, developed using System Verilog on Quartus for an Electrical Engineering lab course.

## Project Overview
In *Road Fighter*, the player controls a racing car with the goal of reaching the finish line before running out of fuel or time. Players can move their car left and right, accelerate, brake, and avoid obstacles like other cars and hazards on the road.

### Key Features
- **Road Generation**: Dynamic generation of road sections with changing background.
- **Car Mechanics**: Player can control the car’s movement (left, right) and speed using keyboard inputs.
- **Collision Detection**: Includes collision detection with other cars and special vehicles (trucks, blue cars).
- **Fuel and Time Tracking**: Displays fuel and time, both of which decrease as the game progresses. Bonus fuel is awarded by interacting with certain cars.
- **Sound Effects**: Includes collision and scoring sounds.
- **Game Display**: Score, time, and fuel are displayed on-screen and on 7-segment displays.

### Development Tools
- **System Verilog**: Main language used for logic implementation.
- **Quartus**: The project is developed and synthesized on Quartus using a VGA interface.
- **VGA Display**: Game graphics are shown on a 640x480 resolution display.
- **FPGA**: Hardware platform used for running the game logic.

### Additional Features
- **Variable Speed Control**: The player can accelerate and brake.
- **Special Vehicles**: Different car types with varied behaviors, including trucks that explode upon collision.
- **Creative Additions**: Support for obstacles like oil spills, road pits, and additional sound effects.

For a demonstration of the project, check out the video here:  
[ROAD FIGHTER Demo](https://youtu.be/PhFJpJJiK0Q?feature=shared)
