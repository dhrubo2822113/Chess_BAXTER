# Chess_BAXTER
Abstract:

This project simulates a chess game using a robot within the Robot Operating System (ROS) and the Gazebo 3D simulator. The virtual environment encompasses a chessboard, pieces, and a table, enabling the robot to interact with the elements. The robot is programmed to pick up and place chess pieces, simulating a real-world chess game.

System Components:

ROS (Robot Operating System):

Provides a framework for robot software development, facilitating communication between different nodes.
Core ROS packages utilized:
rospy: For ROS node creation and message passing.
tf: For maintaining coordinate frames and transformations.
moveit_commander: For robot motion planning and control.
geometry_msgs: For defining geometric data (poses, points).
sensor_msgs: For handling sensor data (vision).
Gazebo (3D Simulator):

Simulates robot dynamics, sensors, and environments.
Used to create the virtual chessboard, pieces, table, and robot model.
Chessboard, Pieces, and Table:

Link to Video :
https://www.youtube.com/watch?v=ErfA32TAdk0&t=24s

Represented as 3D models in Gazebo.
Chessboard: Defined by its size and square dimensions.
Pieces: Modeled with unique shapes and identifiers for recognition.
Table: Provides a platform for the chessboard.
Robot:

Model and simulated behavior defined in Gazebo.
Equipped with a manipulator arm (e.g., gripper) for grasping and manipulating chess pieces.
