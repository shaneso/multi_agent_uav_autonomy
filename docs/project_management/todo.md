### In-Progress

- Design UAV tracker mount in Fusion for prototyping on drone body with Vicon
- Test UAV flight with Vicon motion capture and tracking
- Tracking and Vicon motion capture testing with multiple drone agents
- Waypoint following test for 1 drone
- Waypoint following test for multiple drone agents
- **Nav2** will be used to implement arbitrary trajectory planning for the drone swarms (https://docs.nav2.org/).
- Objective is to set up HIL-verification pipeline to check if drone odometry is good using Vicon motion-capture positioning, then run tests and simulate trajectories in RViz software.
- Set up and connect to Vicon motion capture cameras.
- Build automated pipeline or find a method to control drone trajectories without having to hard code them to the `fcu_mission` files every time.
- Finalize which flight controller firmware to use for drone construction project

### Completed

- Program robots and configure AT modules. Send commands to robots after ROS launches src code with Docker container. It will be running a GUI of RViz to simulate the UAV swarm simulation.
- Configure AT modules on drones
- Review source code of `fcu_core` project software and understand structure (including wsl2, docker, ubuntu, display, xorg).
- Look into source code and docs.
- Sending AT signal to drone + drone IP. UART module to config Wi-fi module on the drones and try to connect drones to Wi-fi in the lab.
- Make a BASH script to run Docker environment with ROS to launch source code.

