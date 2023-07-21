# gazebo_plugin

### Reference material ###
``` https://www.youtube.com/watch?v=Ny66Cna7_YE&list=PLOQhCaBjYnseDMTpd-b52spLSq7hg0ar1&index=2 ```

### Reference repo ###
``` https://github.com/Hrithik-verma/gazebo_plugin_tutorials ```

### Notes ###
1. Gazebo works with publish and subscribe concept same as ROS
2. How to check it? Open ```gazebo``` and run ```gz topic -l command``` to see gazebo topics
3. All message definations are palced at ```home/usr/include/gazebo-11/gazebo/msgs``` folder
4. This folder contains msg defination in 3 files like ```factory.pb.h``` (very important, message class defination) , ```MsgFactory.hh``` , ```factory.proto``` (google protocol buffers used for serial communication, similar to ros msg file)
5. Get details of specific gazebo topic ```gz topic -i /gazebo/default/factory```
6. GUI method to get topic details. Go to gazebo->window->Topic Visualisation and select the topic of interest.
7. Types of plugin
   a. World
   b. Model
   c. Sensor
   d. System
   e. Visual
   f. GUI
9. Standard template is available for these type pf plugin, this needs to be used by derived class to be defined by us for making plugin
10. Important C++ concepts
   a. Namespace
```
    namespace name1{
      namespace name2{
        int  x;
        void funct(){cout<<"hi"<<endl;}
      }
    }
```

How to access

```
name1::name2::x=1;
name1::name2::funct();
```
Example
``` gazebo::physics::World```
gazebo is a namespace

    
12. Gazebo API ```http://osrf-distributions.s3.amazonaws.com/gazebo/api/11.0.0/group__gazebo__physics.html```
13. this point in C++
    Useed to refer to the variables and functions within a class.
    ``` this->id ``` refers to the id which is defined in the class and not the local argument passed to the function
15. aefea
16. fae
17. fae
18. f
19. ae
20. fa
21. ef
22. ae
23. f
24. aef
25. ea
26. f
27. ae
28. a
29. 
