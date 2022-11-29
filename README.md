# hri_game_testbed
A ROS-Gazebo simulation environment to develop and evaluate game-theoretical human-robot interaction behaviors. Intended to be used as part of the game_theory_ws ROS meta-repo.

This is intended to be a drop-in replacement for an actual robot, with similar interfaces and workflows.

# Repo overview
```
/launch # Launch files to initialize the Gazebo testbed
/models # Contains model files of humans and other objects to be placed into the .world environments
/worlds # Contains Gazebo .world files for testing
/maps   # Contains ROS-generated maps of the included environments
```

# Acknowledgements
The hospital world is a variant of Amazon Robotics' robomaker world, originally found here:
https://github.com/aws-robotics/aws-robomaker-hospital-world 

A large collection of other Gazebo worlds is available here:
https://github.com/chaolmu/gazebo_models_worlds_collection 