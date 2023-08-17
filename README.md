# LidarBEV-Segmentation_Fusion
## 202308~

### To Do
- LiDAR BEV (Bird's Eye View)와 2D Panoptic Segmentation 결과 Fusion
- LiDAR point cloud -> 2D Image
- 산업용 PC에 세팅
- bag 파일 재생

---
참조코드:   
https://github.com/beltransen/lidar_bev          
https://github.com/mjshiggins/ros-examples

## LiDAR data -> 2D Image
``` catkin_make ```  
``` source ~/tutorial_ws/src/ros-examples/devel/setup.bash ```  
``` rosrun lidar lidar_node ```  
``` rosbag play -l first_clock.bag ```
