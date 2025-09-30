#  Logistic CoBot (LB) — eYRC 2024-25
![ROS2](https://img.shields.io/badge/ROS2-Humble-blue?logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-Simulation-orange?logo=ros)
![MoveIt2](https://img.shields.io/badge/MoveIt2-Robot%20Manipulation-green?logo=ros)

---

## 📌 Introduction  

The **Logistic CoBot (LB)** is a collaborative robotics project developed for the **e-Yantra Robotics Competition (eYRC) 2024-25**.  
It is designed to simulate **autonomous warehouse operations** such as:  

- Transporting packages between zones  
- Navigating autonomously inside a warehouse  
- Picking and placing objects with a robotic arm  
- Docking and payload handling  
- Coordinating navigation and manipulation in real-time  

The project integrates **ROS2, Gazebo, MoveIt2, Nav2 stack, and UR5 manipulator** to replicate the environment of a real-world **Industry 4.0 warehouse automation system**.  

---

## 🎯 Objectives  

1. Develop a **modular CoBot system** capable of logistics tasks in simulation.  
2. Enable **autonomous navigation** in dynamic warehouse environments.  
3. Implement **motion planning and manipulation** using the UR5 robotic arm.  
4. Design **payload handling services** for attaching/detaching packages.  
5. Showcase a scalable **warehouse simulation** with collaborative robots.  

---

## 🏗️ System Architecture  

The system is built using ROS2 as the backbone, with multiple integrated packages:  




# Logistic coBot (LB) theme for eYRC 2024-25



# Task 1B

To Launch the gazebo-


```sh
ros2 launch eyantra_warehouse task1b.launch.py
```
To launch moveit

```sh
ros2 launch ur_simulation_gazebo spawn_ur5_launch_moveit.launch.py 
```

# Task 1C

### To Launch the gazebo

```sh
ros2 launch eyantra_warehouse task1c.launch.py  
```

### To launch moveit
```sh
ros2 launch ur_simulation_gazebo spawn_ur5_launch_moveit.launch.py 
```

# Task 2a

### To Launch the gazebo

```sh
ros2 launch eyantra_warehouse task2a.launch.py  
```

### To launch moveit
```sh
ros2 launch ur_simulation_gazebo spawn_ur5_launch_moveit.launch.py 
```


# Task 2B

### To Launch the gazebo

```sh
ros2 launch ebot_description ebot_gazebo_task2b_launch.py
```



### To launch rviz
```sh
ros2 launch ebot_nav2 ebot_bringup_launch.py 
```
