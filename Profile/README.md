# Welcome to the GitHub organization for the Space, Automation, Manufacturing Mechanisms lab at University of Florida.  

### If you are a member of the Spring 2023 Smart Manufacturing class, you will find that you have access to the class resources repository, a ROS/MoveIt demo repository, and a few (currently 9) other repositories that are forks of other public repositories.  You don't need to give any attention to the forked repositories unless you are interested in that code too.

### If you use a ROS package with Python code in it, then you may have to switch the default python version in Ubuntu using:
```
sudo update-alternatives --set python /user/bin/python3.8
```
If you get error message in the console about python module not found, then check the python version using:
```
readlink -f $(which python) | xargs -I % sh -c 'echo -n "%: "; % -V'
```
If it says python version 2.something, then switch to python 3.8 (or other python 3 version).
