---
sidebar_position: 2
---

# Basic Locomotion

Locomotion, or the ability to move from one place to another, is a fundamental capability for any mobile robot. For humanoid robots, this often involves walking, which is a highly complex task. This lesson will introduce basic concepts of robot locomotion.

## Types of Robot Locomotion

While humanoids primarily focus on bipedal walking, it's useful to understand other locomotion types:

*   **Wheeled Locomotion**: Simple, fast, and energy-efficient on flat surfaces (e.g., cars, rovers).
*   **Tracked Locomotion**: Good traction on uneven terrain, but slower (e.g., tanks, some industrial robots).
*   **Legged Locomotion**: Offers versatility on varied and uneven terrain, can step over obstacles. Includes bipedal (humanoids), quadrupedal (dogs, horses), and hexapedal (insects) systems.
*   **Aerial Locomotion**: Drones and flying robots.
*   **Underwater Locomotion**: Submersibles and aquatic robots.

## Bipedal Walking Challenges

Bipedal walking in humanoid robots is particularly challenging due to:

*   **Dynamic Balance**: Unlike a wheeled robot, a humanoid robot is inherently unstable and must constantly maintain its balance.
*   **Contact with Environment**: The interaction of feet with the ground involves complex physics (friction, impacts).
*   **Degrees of Freedom**: Humanoid legs have many joints (degrees of freedom), making coordination difficult.
*   **Energy Efficiency**: Walking is metabolically expensive for humans; for robots, it requires significant power management.

## Fundamental Concepts in Bipedal Locomotion

1.  **Zero Moment Point (ZMP)**: A key concept in bipedal locomotion. It's the point on the ground where the robot can apply force without tipping over. Robot control strategies often aim to keep the ZMP within the robot's support polygon (the area defined by its feet on the ground).
2.  **Gait Generation**: This involves planning the sequence of movements for each leg and body segment to achieve a walking pattern. Gaits can be static (slow, always stable) or dynamic (faster, momentarily unstable, relying on momentum).
3.  **Inverse Kinematics**: Calculating the joint angles required to achieve a desired end-effector (foot) position in space.
4.  **Feedback Control**: Using sensor data (e.g., IMU, force sensors) to constantly adjust joint torques and positions to maintain balance and follow the planned gait.

## Simple Locomotion Example (Simulated)

For a basic understanding, consider a very simple wheeled robot or a highly simplified bipedal model in a simulator. The control might involve:

*   **Forward Kinematics**: Given joint angles, calculate the position of the robot's end-effectors.
*   **Open-loop Control**: Pre-calculating a sequence of motor commands and playing them back without real-time sensor feedback (often unstable for humanoids).
*   **Closed-loop Control**: Using sensor feedback to adjust movements, e.g., a PID controller to keep a robot moving in a straight line.

Future lessons will delve into practical implementations of these concepts in various simulation environments.