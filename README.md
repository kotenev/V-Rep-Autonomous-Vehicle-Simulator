# V-Rep-Autonomous-Vehicle-Simulator with ROS


<img src="pictures/1.png"  >
<img src="pictures/gif1.gif"  >

## Instrunction
It's built for Autonomous Vehicle Simulator using V-Rep & ROS simultaneously
It publishes data `Velodyne PointCloud`, `IMU Sensor`, `GPS`, `Localization (X,Y,Z,Heading)`, `Transform (tf)`  
to ROS at the same time as soon as you run the simulation.   

1. move `libv_repExtImu.so`, `libv_repExtRosVelodyne.so` to your V-Rep home folder.  
2. build `libv_repExtRosInterface.so` and move to your V-Rep home folder.  
3. open V-Rep and if there is no error, It's OK  



<br /> <br />
## Topic 
<img src="pictures/2.png" width="400" >
<br /><br />

## Transform Tree(tf tree)
<img src="pictures/3.png"  >



I've used IMU Plugin & Velodyne Plugin from 
https://github.com/bartville/vrep_plugin_imu
https://github.com/omcandido/vrep_plugin_velodyne
<br /><br />

feel free to use as a simulator and if you find any bug while using, report me please Thx :-)
