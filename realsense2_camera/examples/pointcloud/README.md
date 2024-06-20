# PointCloud Visualization
The following example starts the camera and simultaneously opens RViz GUI to visualize the published pointcloud.
```
ros2 launch realsense2_camera rs_pointcloud_launch.py
```

Alternatively, start the camera terminal 1:
```
ros2 launch realsense2_camera rs_launch.py pointcloud.enable:=true
```
and in terminal 2 open rviz to visualize pointcloud.

# PointCloud with different coordinate systems
This example opens rviz and shows the camera model with different coordinate systems and the pointcloud, so it presents the pointcloud and the camera together.
```
ros2 launch realsense2_camera rs_d455_pointcloud_launch.py
```
# 点云可视化
以下示例启动相机并同时打开 RViz GUI 以可视化发布的点云。
````
ros2启动realsense2_camera rs_pointcloud_launch.py
````
或者，启动相机终端 1：
````
ros2启动realsense2_camera rs_launch.py​​ pointcloud.enable:=true
````
并在终端 2 中打开 rviz 以可视化点云。
# 不同坐标系的点云
本示例打开rviz，显示不同坐标系的相机模型和点云，因此将点云和相机一起呈现。
````
ros2启动realsense2_camera rs_d455_pointcloud_launch.py
````