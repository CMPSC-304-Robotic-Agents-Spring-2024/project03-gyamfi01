# Report by Jason Gyamfi

## Tutorials

For each of the following tutorials, please include at least one screenshot of your experience in the tutorial to showcase its completion, and 2-3 sentence reflection.

### [Using colcon to build packages](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Colcon-Tutorial.html)
![Screenshot 2024-03-28 224102](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/3976dc76-9e38-483f-a34d-c8402008ed07)

The command colcon build --symlink-install --merge-install did not properly build. This caused the rest of this tutorial to not work.
: Include a screenshot of a terminal showing subscriber and publisher nodes demo running and 2-3 sentence reflection

### [Creating a workspace](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
![Screenshot 2](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/0202e397-4bbe-405c-adb7-3dd375aa2949)

The command colcon build --merge-install did not work. This caused the rest of this tutorial to not work.
: Include a screenshot showing "MyTurtleSim" (overlay) and 2-3 sentence reflection

### [Creating a package](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html) (Python)
![Screenshot 3](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/51a19f2f-cf04-4829-8128-a80055843062)


The command colcon build --merge-install did not work. This caused the rest of this tutorial to not work.
: Include a screenshot of a terminal showing your package running (output from step 4) and 2-3 sentence reflection

### [Writing a simple publisher and subscriber (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)
![Screenshot 4](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/a7c233af-64c4-474a-8cc3-441492e8fa6c)


The command ros2 pkg create --build-type ament_python --license Apache-2.0 py_pubsub did not work. This caused the rest of the tutorial not to work.
: Include a screenshot of a terminal showing outputs from step 4 and 2-3 sentence reflection

### [Writing a simple service and client (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Service-And-Client.html)
![Screenshot 5](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/619f028a-e3c2-4f04-b228-17e5d262317f)

The command ros2 pkg create --build-type ament_python --license Apache-2.0 py_srvcli --dependencies rclpy example_interfaces did not work. This caused the tutorial not to work.
: Include a screenshot of a terminal showing outputs from step 4 and 2-3 sentence reflection

### [Creating custom msg and srv files](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Custom-ROS2-Interfaces.html)
![Screenshot 6](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/4d741f27-68af-4cde-aee6-d83c0ca6aac7)

The command ros2 pkg create --build-type ament_cmake --license Apache-2.0 tutorial_interfaces did not work. This caused the tutorial not to work.

: Include a screenshot of a terminal showing output from running `py_srvcli service` and `py_srvcli client` and 2-3 sentence reflection

### [Implementing custom interfaces](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Single-Package-Define-And-Use-Interface.html)
![Screenshot 7](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/993636e7-b95f-4556-b722-520034cf4145)

The command ros2 pkg create --build-type ament_cmake --license Apache-2.0 more_interfaces
mkdir more_interfaces/msg does not work. Causing the tutorial not to run.
: Include a screenshot of a terminal showing output from running `topic echo` and 2-3 sentence reflection

### [Using parameters in a class (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Using-Parameters-In-A-Class-Python.html)
![Screenshot 8](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/7139f6a3-4de3-46ea-980b-d66259b14345)

The command ros2 pkg create --build-type ament_cmake --license Apache-2.0 more_interfaces
mkdir more_interfaces/msg does not work. Causing the tutorial not to run.
: Include a screenshot of a terminal showing output from running the node using created launch file (end of step 3.2) and 2-3 sentence reflection

### [Using ros2doctor to identify issues](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Getting-Started-With-Ros2doctor.html)
![Screemshot 9](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/89993806-497d-47bc-98cc-432930e9fe55)

The command ros2 doctor does not work. Causing the tutorial not to run.
: Include a screenshot of a terminal showing output from running the full report and 2-3 sentence reflection

### [Managing Dependencies with rosdep](https://docs.ros.org/en/humble/Tutorials/Intermediate/Rosdep.html)
![Screenshot 10](https://github.com/gyamfi01/project04-gyamfi01/assets/112565160/a6198784-81cd-45ce-833d-353747a4f835)

THe command apt-get install python3-rosdep does not work. Furthermore, the website states rosdep does not work on windows which is what I am operating on.

: Include a screenshot of a terminal showing `rosdep` installation and 2-3 sentence reflection

### [Creating an action](https://docs.ros.org/en/humble/Tutorials/Intermediate/Creating-an-Action.html)

TODO: Include a screenshot of a terminal showing output from step 2 and 2-3 sentence reflection

### [Writing an action server and client (Python)](https://docs.ros.org/en/humble/Tutorials/Intermediate/Writing-an-Action-Server-Client/Py.html)

TODO: Include a screenshot of a terminal showing output from running the action client and 2-3 sentence reflection

## Challenges and Learning Experiences
The assignment has given me trouble throughout the whole time I have tried to run it. Different commands just not working was really frusturating. Not being able to get to the bottom of it was even more frustrating.
: Discuss any challenges you have encountered during the work on this assignment and describe the biggest learning takeaways.
