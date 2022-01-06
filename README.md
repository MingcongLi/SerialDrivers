This is a repo publishing several of our sensors which may be installed on our vehicle.
These sensors include WindSpeed sensor, MiranLength sensor and DigitalProtractor.
The signals of all of these sensors are transmitted via RS232 or RS485 serial and converted to USB.
Any question please contact mingcong.li@plus.ai

1. clone this repo under a catkin workspace src dir, such as ~/catkin_ws/src/

2. make sure drive docker is updated to the latest, and internet is connected

3. (roscore in another terminal, or connect to ros master)

4. cd $(THE_CATKIN_WORKSPACE)

5. bash $(CATKIN_WORKSPACE)/src/SerialDrivers/launch_serial_docker.sh

6. to install those packages, bash $(CATKIN_WORKSPACE)/src/SerialDrivers/preparation_for_launching_driver.sh

7. to run miran sensor directly, bash $(CATKIN_WORKSPACE)/src/SerialDrivers/run_miran_sensor_node.sh

Note that these codes are originally copied from internet and modified by my friend Jintao Zhao and myself, and only used by me in vehicle testing while containing no intellectual property from PlusAI. Anyone is welcomed to use the code and modify it freely by themselves.
