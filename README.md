# 操作指南

**此SDK用于实验教学。**

原作者：[链接](https://github.com/AlessioMorale/ld06_lidar.git)

ROS版本：ROS melodic

## 编译

```bash
# 切换到工作空间下
$ cd ~/catkin_ws/src

# 下载源码
$ git clone https://github.com/withhold17/TeachingCar.git

# 安装sdk需要的依赖
$ apt-get install libudev-dev

# 编译
$ cd ~/catkin_ws
$ catkin_make -DCATKIN_WHITELIST_PACKAGES="ld06_lidar"
```



## 运行

```bash
# 查看激光雷达数据（打开配置好的rviz）
$ roslaunch ld06_lidar view_ld06.launch

# 启动激光雷达
$ roslaunch ld06_lidar ld06.launch
```
