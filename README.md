# SDF_to_URDF_Coverter
As Gazebo support only sdf format and Ros works with urdf format most of the time. so here you can use this repo to change your sdf
file into urdf.

# what you need to change - 
1. inside parse.py file change your ROS workspace and Gazebo models directory.
2. And put your sdf file into same directory as sdf2urdf file and also create a empty urdf file.
3. Now just run sdf2urdf file.
check your urdf file. it contains xml content corresponding to your sdf file.
