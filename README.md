# Unity-Joystick-GUI
Unity Joystick GUI used for many Robot Simulations

## Input System Workflows
- There are multiple ways to use the Input System. One way is to read device states directly. This workflow is a simplified, script-only approach which bypasses the Actions and Bindings features entirely. Instead your script explicitly references specific device controls (such as "left gamepad stick") and reads the values directly. This is suitable for fast prototyping, or single fixed platform scenarios. It is a less flexible workflow because it bypasses some of the main input system features... [Input System Workflows](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.19/manual/Workflows.html)
- The **Joystick GUI** has been used in Youtube videos to show the robot's input while demostrating the robot's actions. Although the keyboard inputs can do the samething but difficult to demostrate input - output correlations.

## Mouse Input
- Simulations and Study
  - Arduino 5 volt Simulation
    - Joystick potentiometer X
    - Joystick potentiometer Y
  - Joystick Positions
  - Joystick sub-unit 2D Vector
  - Joystick Algorithm
    - Input: Joystick Positions
    - Output: **Left** and **Right** for a differential drive wheeled mobile (DWMR) robot fpr motor like values.

## Keyboard Input
- WASD keys
  - AD keys: Horizontal movement
  - WS keys: Vertical movement
- Kinematics - Math
  - ***TODO***: Design kinematic movement with Keybpard WASD keys input similarly to the Joystick Algorithm Mouse Input.
 
## Example Unity Grahics
- Gameobjects
  - In Progress

## Critics Review about MageMCU Joystick Algorithm
- Pros
  - **Multi-Platform Support**: The underlying engine often provides broad compatibility with arbitrary joysticks and gamepads, allowing it to seamlessly bridge physical hardware to virtual environments.
  - **User-Friendly Remapping**: It frequently includes intuitive mapping features and dead-zone configurations, ensuring players can adapt inputs to their precise liking.
  - **Macro System**: It simplifies complex controller behaviors by enabling macros or stringing commands together to optimize gameplay.
  - **Python Scripting**: For advanced users, it allows custom modules and unlimited customization via Python scripting.
- Cons
  - **Hardware Limitations**: Since game controllers can vary wildly in naming and button arrangements, users sometimes report mapping and gamepad recognition issues that require manual fiddling.
  - **Complex UI Configuration**: While intuitive once set up, diving deep into the raw algorithm can be overwhelming for users who simply want plug-and-play functionality.
  - **Inconsistent Calibration**: Uncalibrated joysticks (or varying thresholds across different game engines) can lead to drift, missed inputs, or jittery character movements.

## Platform
- Unity 6.3 LTS
- Editor: [VS Code](https://code.visualstudio.com)
- 
## Purpose
- Used by authur to study input-ouput devices (sensors & actuators respectively) in DWMR simulations.
- This Unity Project is given freely for developers to experiment in robotics.

## In Progress
