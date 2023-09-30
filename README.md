# small-ros-car-new
new ros car
环境：ubuntu20.04 ros noetic
创建新的工作空间，将这个三个个功能包放入src，编译
运行打开节点：roslaunch urdf02 my_car.launch 
运行键盘控制：
rosrun teleop_twist_keyboard teleop_twist_keyboard.py _speed:=0.8 _turn:=1.2
Moving around:
   u    i    o
   j    k    l
   m    ,    .


