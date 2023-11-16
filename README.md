# Miaowang_Board 三模机械键盘
这个不是从功能性的定义出发去构思的一个项目。是我个人为了去了解一些技术方案，锻炼一系列技能，把这些所有的个人需求拼凑在一起，创造出了这么一个项目。  
  
它是一个带有两块屏幕的三模机械键盘，左边大的长条屏是Android系统的显示器，右边的小屏幕显示与电池包有关的电源管理信息。充电功率支持最大30W（PD协议），放电功率支持最大100W（PD协议）。
![final](https://github.com/wang-miaow/Miaowang_Board/assets/69497364/9a923339-30dc-42e2-809d-7f0bace865c6)  
![IMG_4374](https://github.com/wang-miaow/Miaowang_Board/assets/69497364/6ad0c736-db91-4ff5-8134-9ca2c71ef595)

  
机械键盘部分使用CH582M作为主控，支持USB，蓝牙，2.4G三种连接模式。Android部分是运行在瑞芯微的RK3399平台上，另使用一个STM32F4芯片作为电源管理系统的控制及UI显示。  
  
结构上，机械键盘部分使用Gasket Mount结构，并在定位板和PCB上开槽实现整体手感和按键音优化。键盘上壳是用尼龙材料3D打印，喷漆由于技术问题，有很多瑕疵。底壳使用了一块亚克力板，通过螺丝与上壳固定。  
![image](https://github.com/wang-miaow/Miaowang_Board/assets/69497364/be67f115-b268-401b-82a5-741440c277b9)
