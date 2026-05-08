# PhysiBall

# Project Overview
PhysiBall is an interactive simulation developed in C++ with the Grapic library. The project simulates launching a projectile in a space environment where the user must destroy targets while managing physical forces like gravity, friction, and collisions with moving obstacles.

# Interface Sections
The interface is divided into two distinct areas:

Simulation Zone (Space): Contains the launcher, the ball, orange targets, and their protective satellites.

Dashboard (Analytics): Displays real-time statistics and the dynamic changes of physical variables.

# Implemented Features

## Physics and Dynamics
Gravity and Friction: Simulation of weight and air resistance.

Elastic Launcher: A spring-based system with damping to stabilize the ball before launch.

Collisions: Management of elastic bounces on the ground and against asteroids.

Trajectory Prediction: A dotted line shows the calculated path of the ball.

## Analysis and Data
The side panel allows you to track exactly how the object behaves:

Altitude and Velocity Graph: A live comparison of height and speed over time.

Phase Diagram: A visual map of velocity vs altitude to observe movement cycles.

Statistics: Real-time display of Score, VMAX (maximum speed), and a stopwatch.
