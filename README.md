# Unity-Joystick-GUI
Unity Joystick GUI used for many Robot Simulations

## Input System Workflows
- There are multiple ways to use the Input System. One way is to read device states directly. This workflow is a simplified, script-only approach which bypasses the Actions and Bindings features entirely. Instead your script explicitly references specific device controls (such as "left gamepad stick") and reads the values directly. This is suitable for fast prototyping, or single fixed platform scenarios. It is a less flexible workflow because it bypasses some of the main input system features... [Input System Workflows](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.19/manual/Workflows.html)
- The Joystick GUI has been used in Youtube videos to show the robot's input while demostrating the robot's actions. Although the keyboard inputs can do the samething but difficult to demostrate input - output correlations.

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
    
## In Progress
