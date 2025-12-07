---
sidebar_position: 4
---

# "Hello, Robot!" - A Simple First Project

Now that your development environment is set up, let's create your very first robotics project! This "Hello, Robot!" example will introduce you to basic programming concepts in a robotics context.

## Project Goal

To write a simple program that makes a simulated robot perform a basic action, like moving a joint or printing a message to the console.

## Tools You'll Need

*   Your configured development environment (Node.js, npm/yarn, VS Code).
*   A simulator (e.g., Webots, Gazebo, or a simpler library if available). For this initial example, we'll focus on a text-based output, abstracting the physical robot for simplicity.

## Step 1: Create Your Project Directory

Navigate to a suitable location on your computer and create a new directory for your project:

```bash
mkdir my-first-robot
cd my-first-robot
```

## Step 2: Initialize a Node.js Project

Since we're familiar with Node.js from our Docusaurus setup, let's use it for this project.

```bash
npm init -y
```

This command creates a `package.json` file, which manages your project's metadata and dependencies.

## Step 3: Write Your "Hello, Robot!" Code

Create a new file named `index.js` in your `my-first-robot` directory.

```javascript
// index.js
console.log("Hello, Robot!");
console.log("Initializing robot...");

// Simulate a simple robot action (e.g., moving a joint)
function moveJoint(jointName, angle) {
    console.log(`Moving joint '${jointName}' to angle ${angle} degrees.`);
    // In a real robot, this would send commands to motors
}

moveJoint("shoulder_pitch", 30);
moveJoint("elbow_yaw", -45);

console.log("Robot actions complete. Goodbye!");
```

## Step 4: Run Your Program

Execute your script from the terminal within the `my-first-robot` directory:

```bash
node index.js
```

You should see output similar to this:

```
Hello, Robot!
Initializing robot...
Moving joint 'shoulder_pitch' to angle 30 degrees.
Moving joint 'elbow_yaw' to angle -45 degrees.
Robot actions complete. Goodbye!
```

## Congratulations!

You've successfully run your first "robot" program. While this is a simulated, text-based example, it demonstrates the fundamental concept of sending commands and receiving feedback. In future lessons, we'll connect these programming concepts to actual robot simulators and hardware.