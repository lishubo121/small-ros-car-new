# small-ros-car-new
new ros car

该代码仓库为在哔站进行ros学习的过程中搭建的urdf文件，分享给大家，求个star。

参考链接：http://www.autolabor.com.cn/book/ROSTutorials/di-6-zhang-ji-qi-ren-xi-tong-fang-zhen/67/674-kinectxin-xi-fang-zhen-yi-ji-xian-shi.html

视频链接：https://www.bilibili.com/video/BV1Ci4y1L7ZZ?p=289&spm_id_from=pageDriver&vd_source=477f94c98e6a4844404f01c32c6c2458

环境：ubuntu20.04 ros noetic

创建新的工作空间，将这个三个个功能包放入src，编译:catkin_make

运行打开节点：roslaunch urdf02 my_car.launch 

运行键盘控制：
rosrun teleop_twist_keyboard teleop_twist_keyboard.py _speed:=0.8 _turn:=1.2
