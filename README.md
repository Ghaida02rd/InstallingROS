# InstallingROS

## Requirement
* [VirtualBox](https://www.virtualbox.org)
* [Ubuntu](https://ubuntu.com)
* [ROS](https://www.ros.org)

# Steps:
 Open VirtualBox and creat a new machine and add ubuntU image.

![image](https://github.com/user-attachments/assets/a49841e2-fb3d-4b35-a983-82ad3e3d94d6)

 Select the Memory size (RAM) 4 GB or more and Hard disk size 30 GB or more.

 ![image](https://github.com/user-attachments/assets/8b474eb8-cda1-4042-a227-fba282da5195)


Click start and install ubuntu
![image](https://github.com/user-attachments/assets/4737e6ec-4ea5-4297-a1ab-11ad8c75946d)

# ROS
After installing, open the terminal to instal Ros1

1. Setup your sources.list
 ```sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'```

2. Set up your keys
 ```sudo apt install curl ```
 ```curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -```

3. Installation (make sure package index is up-to-date:)
    ```sudo apt update ```
   Download Ros desktop full
   ```sudo apt install ros-noetic-desktop-full ```

4. Environment setup
``` source /opt/ros/noetic/setup.bash```

5. Dependencies for building packages
```sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential```
Initialize rosdep
```sudo apt install python3-rosdep```
```sudo rosdep init```

```rosdep update```

# To check Ros installation 
```roscore```

![image](https://github.com/user-attachments/assets/a20ccf9b-d01d-40b9-b181-74a5545efb0c)



   
