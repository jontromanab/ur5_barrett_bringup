The launch files for bringing up the UR5_Barrett robot and the kinect in gazebo. The urdf will be taken from the ur5_barrett_description package. After downloading the package to the catkin_workspace, catkin_make the files. To launch the robot in gazebo:

	roslaunch ur5_barrett_bringup robot_bringup.launch


There are a few test files provide to test the hand and the arm. Python nodes are provided in the scripts folder.
To test the ur5:

	rosrun ur5_barrett_bringup simple_trajectory


to test the barrett hand:

	rosrun ur5_barrett_bringup simple_trajectory_bhand


to test the python nodes:

	rosrun ur5_barrett_bringup stow_ur5_new
