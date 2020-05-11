# creating a node

we need these line in the file
#!/usr/bin/env python
import rospy

## initialize the ROS node
    rospy.init_node('talker', anonymous=True)
 ### when anonymous is true it will append a unique no to ros node name 
 when will print the rosnode list the output like
  node_name_6625_1550398083304 
  
 # if anonymous is true:
   If you start this same node in another terminal, the previous one will be killed
 # else:
  when anonymous is true when we have an option like using multiple terminals 
