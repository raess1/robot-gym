# robot-gym
RL and classical techniques applied to robotics.



#requirements python3.7

#Installation

Create a Python 3.7 virtual environment, e.g. using Anaconda

``conda create -n [envname] python=3.7 anaconda``

``conda activate [envname]``


#Install from source

Clone this repository and run from the root of the project:

``git clone https://github.com/raess1/robot-gym.git``

``cd robot-gym``

``git checkout k3lso-stable``

``pip install .``



``Usage: robot-gym playground [OPTIONS]

Options:  
  -r, --robot [ghost|k3lso]     The robot you want to use.  
  -m, --mark TEXT               Set the robot mark (version).  
  -rec, --record-video BOOLEAN  Record a video clip (mp4).  
  -pad, -g, --gamepad BOOLEAN   Control the robot using a gamepad.  
  --help                        Show this message and exit.  
``



Notes for shapely

``conda config --add channels conda-forge ``

``conda install shapely``



**Notes for debug output. (robot-gym/robot_gym/model/robots/simple_motor.py)**  
#Debug output (q, qdot, kp, kd, tau) (Postion, velocities, PID gains, motor torque)






### Quadruped Playground Demo
[![playgroud](https://img.youtube.com/vi/n8vaPM3yBlY/0.jpg)](https://www.youtube.com/watch?v=n8vaPM3yBlY)

### Quadruped Go-To taks
[![playgroud](https://img.youtube.com/vi/OVI9DYjW12k/0.jpg)](https://www.youtube.com/watch?v=OVI9DYjW12k)

