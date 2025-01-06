## ir-sim 2.3.1

- Add FOV for the object (doc require), see usage 16fov_world for detail
- Add Arguments for function WrapToPi
- Add the role selection for the rvo behavior (doc require)
- Update Documentation (Fov, noise world, path manager)
- Fix some bugs

## ir-sim 2.3.0

**Major Version Update:** 

- Public the documentation for the project.
- Add the coverage test for the project.
- Reformulate the kinematics handler and geometry handler to configure the robot and obstacles.
- Reorganize the lidar2d step function to make it faster.
- Update the comments for the functions.
- Fix some bugs in the project.
- Add 3d plot environment.

## ir-sim 2.2.6

- Reformulate the behavior lib, add custom behavior interface, see usage 13custom_behavior for detail
- Add default name for the yaml file; default name is same with the python script; see usage: 12dynamic_obstacle for detail
- Change the trajectory visualization style; see usage 02robot_world for detail
- Reconstruct the save_figure function; see usage 07renderw_world for detail
- Fix the bug of 'display' in the env.end() function.

## ir-sim 2.2.5

- Convert the GIF file to readme links to reduce the repository size
- Modify the visualization of the arrow for the robot
- Adjust figure size by pixel
- Add reset for world time
- Change the matplotlib backend to TkAgg
- Fix some bugs on the visualization

## ir-sim 2.2.4

- Fix collision avoidance bug for obstacles
- Arrange the kinematics functions
- Add the state_shape and vel_shape for object_base
- Format all python code with black
- Complete the function comments and generate api documentation

## ir-sim 2.2.3

- Rename the module name from ir_sim to irsim, rename the package name from ir_sim to ir-sim
- Add citation for the project
- Refine the comments for the functions
- Configure the readthedoc and sphnix for documentation
- Add the attribute unobstructed for obejcts, see usage: obstace_world for detail
- Fix the state_dim bug

## ir-sim 2.2.0

- Rename the module from ir_sim to irsim, rename the package name from ir_sim to ir-sim
- Add citation for the project
- Refine the comments for the functions


## ir-sim 2.1.4

- Update function comments
- Update the readme
- Add interface to change the object distribution in the environment
- Add Feature of obstacles random in the environment

## ir-sim 2.1.3
- Fix errors in usages
- delete some old files
- Fix some bugs

## ir-sim 2.1.2

- Fix bug for omni dynamics robots
- Fix bug for rvo behavior
- Replace the diff description for the object_base


## ir-sim 2.1.1

- Update the YAML API
- Enhance features in object_base (G, h)
- Expand project development utilities
- Fix some bugs

## ir-sim 2.1.0

Big Version

- Reformulate the whole project framework, all the objects are developed by the object base
- Using shapely to construct the geometry for the robot and obstacles
- Reconstruct the YAML interface
- Add the behavior library for the objects
- Add the object factory to create the objects
- Add env logger to record and print the environment status

## ir-sim 1.1.12

Update the refresh of the show_trail
Add set robot goal method
Fix some bugs


## ir-sim 1.1.11

Add the function to change the edgecolor
Add repeat mkdirs
Fix some bugs

## ir-sim 1.1.10

- Fix some bugs
- Add the collision mode 'unobstructed'
- Add draw box function
- Add radius for obstacle


## ir-sim 1.1.9

- Fix some bugs
- Add features for obstacles.


## ir-sim 1.1.8

- Add map obstacles
- Fix bugs of reset robot
- Add different car models

## ir-sim-v1.1.7

- Fix bugs of pyproject.toml