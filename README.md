Installation:
```
- rosdep install --from-paths src --ignore-src -r -y
- sudo apt-get install ros-noetic-trac-ik-kinematics-plugin
- catkin build
```
Docker build: takes time! Build at the beginning of the class:

```
- sudo .docker/build_image.sh 
- sudo .docker/run_user.sh
- sudo chown -R grogu /dev_ws
