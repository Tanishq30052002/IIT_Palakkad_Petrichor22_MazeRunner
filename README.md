# IIT_Palakkad_Petrichor22_MazeRunner

## Welcome the our Git Repository of Maze_Runner !!!

## Steps to use our Git repository
1. Create a folder in your device named catkin_ws.
2. Open the terminal there itself.
3. Write the folowing command in the terminal :- 
	*	~~~
		git clone https://github.com/Tanishq30052002/IIT_Palakkad_Petrichor22_MazeRunner.git
		~~~
4. Now rename the folder to "mobot_description".
5. Now use the command `catkin_make` in yout eYRC_ws folder to make it a ROS workspace.
	*	~~~
		catkin_make
		~~~
6. Write the folowing command in the terminal :- 
	*	~~~
		cp -a ~/catkin_ws/src/mobot_description/models/. ~/.gazebo/models
		~~~
6. Remember to source the workspace everytime before use by the following command :- 
	*	~~~
		source devel/setup.bash
		~~~
7. Congo :partying_face:
8. You are all set up with the workspace.

## Run the Maze Runner
1. 
