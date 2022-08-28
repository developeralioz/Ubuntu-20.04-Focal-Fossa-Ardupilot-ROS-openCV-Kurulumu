# Ubuntu 20.04 (Focal Fossa) üzerine ArduPilot, ROS Noetic, openCV, Dronekit Kurulumu
Ubuntu 20.04 (Focal Fossa) üzerine ArduPilot, ROS Noetic, openCV, Dronekit Kurulumu

`sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`

`sudo apt install curl`

`curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
`
`sudo apt update
`

`sudo apt install ros-noetic-desktop-full
`
