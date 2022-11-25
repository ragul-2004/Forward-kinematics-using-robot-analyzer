# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.open the roboanalyzer software.<br>
2.select the robot and its degrees of freedom.<br>
3.change the values with the link lenght wherever necessary.<br>
4.simulate the model for forward kinematics.<br>
5.plot the graph between the link and the joints.<br>
6.update the DH parameters of the link configuration and end effector configuration.<br>




### SIMULATION :

 #### 4DOF
 
![image](https://user-images.githubusercontent.com/75235402/199652855-390aa418-65ac-4711-a2cc-fbad36e335dd.png)

 #### 6DOF
 
 ![image](https://user-images.githubusercontent.com/75235402/199652703-ce0944a7-7ce4-436f-bc2d-2f253e961af9.png)

 
 
 
 ### PLOT :
 
 
 ### 4DOF

 ![image](https://user-images.githubusercontent.com/75235402/199652300-d23d83d2-b6d0-4c80-a1ea-8f0896b780e4.png)

 
  ### 6DOF
 
 
 ![image](https://user-images.githubusercontent.com/75235402/199652662-8b3f95c0-58c6-45eb-ad2c-fc45f65bd529.png)

 
 
 
 

 
 














### RESULTS :  

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
