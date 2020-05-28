## tum_simulator ported to Ros Melodic and Gazebo 9
The original code was written in hydro which can be found here :
https://github.com/tum-vision/tum_simulator.git
This is a ros melodic version of the code.
Tested on Ubuntu 18.04.1, ROS Melodic and using Gazebo 9.
How to run a simulation:
1. create a package
* `mkdir -p catkin_ws/src/`
* `cd catkin_ws/src/`
* `catkin_init_workspace`
2. Clone the required repositories
* `git clone https://github.com/surajmahangade/tum_simulator_melodic.git`
* `git clone https://github.com/dsapandora/ardrone_autonomy.git`
3. Build
* `cd ~/catkin_ws`
* `catkin_make`
4. Run the simulation
Run a simulation by executing a launch file in cvg_sim_gazebo package: 

* `roslaunch cvg_sim_gazebo ardrone_testworld.launch`

