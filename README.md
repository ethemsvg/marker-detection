# Description
Zed stereo camera and OpenCV library are used to detect ARUCO Markers. For better recognition, Adaptive histogram equalization applied. <br/>
For one marker, the position of the middle point of the ARUCO Marker is published as a ROS Topic.  
For 2 markers, the position of the between point of the markers is published as a ROS Topic.

 <br/>

## GTU Rover
This ROS package was made for use in the [GTU Rover](https://youtu.be/uv-LEvk_AX8?t=205) team's URC competition.  

 <br/>

# Screenshots
![Marker Detection](images/3.png)
**Marker Detection - You can see the position information of the middle point of the marker on the right side.**   
<br /> <br />

![Between Point Detection - Close](images/1.png)  
**Between Point Detection - You can see the position of the between point of the markers as a red dot. Information of the position is also published as ROS topic**   
<br /> <br />


![Between Point Detection - Far](images/2.png)
**Between Point Detection - You can see the position of the between point of the markers as a red dot. Information of the position is also published as ROS topic**    
