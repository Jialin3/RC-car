## 1. Prerequisites
### 1.1 **Ubuntu** and **ROS**
**Ubuntu == 20.04**

**ROS == Foxy**

### 1.2. **PCL && Eigen**
PCL    >= 1.8,   Follow [PCL Installation](https://pointclouds.org/downloads/#linux).

Eigen  >= 3.3.4, Follow [Eigen Installation](http://eigen.tuxfamily.org/index.php?title=Main_Page).

### <span id="1.3">1.3. **livox_ros_driver2**</span>
Follow [livox_ros_driver2 Installation](https://github.com/Livox-SDK/livox_ros_driver2).



## 2. Build
### 2.1 安装和编译**Livox-SDK2、livox_ros_driver2 **
1. Livox-SDK2：
```shell
$ git clone https://github.com/Livox-SDK/Livox-SDK2.git
$ cd ./Livox-SDK2/
$ mkdir build
$ cd build
$ cmake .. && make 
$ sudo make install
```



