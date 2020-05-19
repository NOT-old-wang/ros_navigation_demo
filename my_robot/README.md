## 机器人配置
[wiki](http://wiki.ros.org/navigation/Tutorials/RobotSetup)

## 相关节点
### 1. map_server
- map_server 使得地图的数据变成 ros 的 service 可以被调用
[](https://www.cnblogs.com/xialuobo/p/6104019.html)
### 2. amcl 定位

### 3. move_base 导航
[wiki](http://wiki.ros.org/move_base/))

### 4. 模拟器 stage_ros
[wiki](http://wiki.ros.org/stage_ros)
```
1: 加载地图, 放入机器人
2: 模拟发出 scan, odom 数据
3: 接收 /cmd_vel 控制机器人移动
```

### 5. rviz 可视化工具
[参考](http://wiki.ros.org/cn/navigation/Tutorials/Using%20rviz%20with%20the%20Navigation%20Stack)
