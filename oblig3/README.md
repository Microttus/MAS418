#Oblig 3 submission 

##ROS
All ros source files are availabel in the src folder. 

ROS steps:
- Build and source local setup
```
colcon build
. intsall/setup.bash
```
- Launch the green crane node and cross out the gui window
```
ros2 launch urdf_tutorial display.launch.py model:=`ros2 pkg prefix --share urdf_tutorial`/urdf/green_crane.urdf
```
- In a new terminal window launch dispal the pressure topic
```
ros2 topic echo /pressure_states
```
- Launch the ads_node
```
ros2 run ads_example_package ads_node
```

Finally, be amazed :) 

##Twincat
All files for the twincat part can be found in the folder MAS418_LAB1

Note: The simualtion neds to to activated in twincat
