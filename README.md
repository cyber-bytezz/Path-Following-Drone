# Path Following Drone in CoppeliaSim

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CoppeliaSim](https://img.shields.io/badge/CoppeliaSim-v4.2.0-blue)](https://www.coppeliarobotics.com/)

## Introduction

This repository presents a sophisticated simulation of a Path-Following Drone in CoppeliaSim, a state-of-the-art robotics simulator. The project showcases the seamless integration of Path-Following Algorithms, offering a robust platform to test and refine drone control strategies in a simulated environment.

![Demo Video](https://github.com/cyber-bytezz/path-following-drone/assets/130319315/906d18f1-0149-46b1-8fc6-390a0dbbc7c3)

## Features

- **Path Generation and Visualization**: Create and visualize intricate flight paths with ease.
- **Advanced PID Controller**: Employ a precise PID controller for altitude and position control, ensuring optimal flight performance.
- **Dynamic Obstacle Avoidance**: Navigate dynamically changing environments with intelligent obstacle avoidance algorithms.
- **Interactive GUI**: Utilize a user-friendly interface for seamless user input and visualization.

## Prerequisites

- [CoppeliaSim v4.2.0](https://www.coppeliarobotics.com/) - Ensure you have the latest version of CoppeliaSim installed.

## Getting Started

1. **Clone this repository**:

   ```bash
   git clone https://github.com/yourusername/path-following-drone.git
   ```

2. **Open the CoppeliaSim Scene**:

   - Launch CoppeliaSim and load the scene file `path_following_drone.ttt`.

3. **Start the Simulation**:

   - Initiate the simulation within CoppeliaSim.

4. **Run the Control Script**:

   - Execute the control script `path_following_drone_control.lua`.

## Usage

1. **Configure Path and Parameters**:

   - Use the interactive GUI to set the desired flight path and parameters.

2. **Initiate Flight**:

   - Press the "Start" button to commence the drone's movement along the specified path.

## Configuration

- `config.yaml`: This file contains crucial configuration parameters influencing the drone's behavior and control.

## Most Interesting Aspects

### Realistic 3D Environment

Explore a meticulously designed 3D environment that mimics real-world conditions, providing an immersive testing ground for your drone algorithms.

### Adaptive Obstacle Avoidance

Experience the drone's ability to dynamically adapt and navigate around obstacles, showcasing its intelligent decision-making capabilities.

### Performance Tuning with PID Controller

Fine-tune the drone's performance using an advanced PID controller, allowing for precise altitude and position control, even under challenging conditions.

## Contributions

Contributions are welcomed! For major changes, please initiate a discussion by opening an issue.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](LICENSE) file for details.
