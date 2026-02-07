# Handheld-Soft-Robotic-Grabber
A handheld grabber using soft robotic concepts paired with digital control.


# Soft Robotic Grabber

## Overview
A user-controlled soft robotic grabber inspired by consumer mechanical grabbers and soft robotic grippers.

## Project Goals
- Create a compliant gripper capable of grasping everyday objects
- Use low-cost, hobbyist-friendly components
- Emphasize control and mechanical design over automation
- Improve understanding of Arduino microcontroller functions

## Constraints
- 3-week build time
- Arduino-based control
- Minimal prebuilt purchases

## System Overview
The system consists of a user input mechanism, a microcontroller for signal processing, a motor-driven actuator, and a compliant soft gripper. A block diagram will be added once major components are selected.

## Mechanical Design
The mechanical design focuses on compliance and simplicity. The gripper will be fabricated using flexible materials (TPU) and actuated through a single motor-driven mechanism.

Key design considerations:
- Gripper compliance vs control precision
- Single-actuator simplicity
- Manufacturability using basic tools and 3D printing

## Electronics
The electronics subsystem is based around an Arduino microcontroller. Actuation will be handled using an external motor driver to avoid loading microcontroller pins.

Planned components include:
- Arduino Uno or Mega
- Motor driver (TBD)
- Motor type (TBD)
- External battery supply

## Control Logic
The control strategy emphasizes proportional user control rather than discrete open/close motion. User input will be read as an analog signal and mapped to motor speed or position.

Planned features:
- Proportional actuation
- Deadzone handling
- Soft start/stop behavior

## Prototyping & Iteration
### Initial Concept
The initial concept was inspired by mechanical trigger-style grabbers and soft robotic grippers. The goal was to merge the intuitive user control of a consumer grabber with the compliance of a soft end-effector.

### Early Design Questions
- How should force be transmitted to a soft gripper?
- How much compliance is desirable before control becomes unpredictable?

## Results
(To be added)

## Limitations
- Gripper force is limited by motor torque and material compliance
- Lack of force feedback results in inconsistent grip strength
- Mechanical tolerances from 3D printing reduced repeatability
  
## Future Improvements
- Add force sensing for closed-loop grip control
- Redesign gripper fingers for improved durability
