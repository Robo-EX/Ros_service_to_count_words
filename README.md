# Ros_service_to_count_words

FIRST CREATE THE NEW PACKAGE IN CATKIN_WORKSPACE SRC FOLDER
```shell
catkin_create_pkg practice rospy
```
#### Once Package Is Created git clone ....and then run catkin_make  
### CHECKING THAT EVERYTHING GOES AS EXPECTED
```shell
rosrun practice service_server.py
```
### USING A SERVICE
```shell
rosservice all word_count 'abc def ghi'
```
