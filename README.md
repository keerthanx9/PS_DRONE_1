Problem Statement
Autonomous delivery and inspection drones operating in dense urban environments frequently lose reliable GPS signals near tall structures and encounter unmapped static or dynamic obstacles. The objective of this project is to design, simulate, and validate a closed-loop guidance, navigation, and control (GNC) pipeline that enables a quadrotor UAV to navigate from a launchpad to a target landing zone in a cluttered, GPS-degraded 3D environment, avoid obstacles in real time, and execute a precision landing within a 0.5-meter error radius while minimizing energy consumption and flight time.

Core Simulation Components

    Environment & Physics: A 3D urban-canyon or obstacle-field world with quadrotor dynamics, wind disturbances, and sensor noise.

    Perception & Planning: Simulated onboard sensing (LiDAR/depth or optical flow) paired with a local path planner (e.g., A*, RRT*, or artificial potential fields) and PID/MPC flight controller.

    Validation Metrics: Mission success rate, collision count, trajectory smoothness, landing accuracy, and battery/energy usage across randomized obstacle layouts.
