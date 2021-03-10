This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website. <br>
-------
*宠物自动喂食器开发计划书*
======
应用场景 <br>
-------
#### 随着生活水平的提高，养宠物的家庭越来越多，但每个人都不是时时刻刻有空照顾到其宠物的生活饮食；为此，正对上班族，短暂旅游族，懒懒的铲屎官们照顾宠物的饮食，所特定的研发一款智能宠物自动喂食器; <br>
功能 <br>
----------
#### 定制计划:可通过控制板的按键与显示，制定一天/一周的喂食计划； 
#### APP监控：在APP上可实时监控干粮与水的余量，宠物器上饮水槽与粮食槽的余量，并可手机定量投食； 
#### 数据收集报告：开启此模式，会汇总一周内宠物的饮食行为，比如一天内的饮水与粮食的量度，饮食时间，发送到手机供主人了解与分析宠物的状况； 
#### 陪玩模式：APP控制宠物器，宠物器通过RF433远程开启逗猫器，让宠物运动起来（适合猫，狗，需要空间大一点，逗猫器离喂食远一点） <br>
硬件 <br>
----------
#### 采用STM32最小系统板，语音模块（可选）；自身开发过的控制板，带按键，RF433与显示；WIFI蓝牙模块；步进电机；距离感应模块；光感模块；LED灯条或灯； 霍尔开关；三明治开发套件<br>
开发思路<br>
----------
#### 移植tuya平台IOT模块打通程序与硬件；设置自动投食与饮水开关，可手动喂食，手机APP控制，自动检测模式；  
#### 自动检测模式由霍尔开关设置，通过食物与水的重量，采用支点式移动霍尔并检测；提供数据让繁忙的主人了解宠物的状况；  
#### 陪玩模式：考虑宠物活动范围较大，需要离喂食的地方远一些，避免碰倒；
开发周期 <br>
-----------
##### 3月14号前，挑选并确认模块，了解，熟悉与移植IOT开发难点，打通软件，为下面做铺垫 <br>
##### 3月15~21号，调试样机，加以整改；考虑外壳设计（看开发进度与功能而定是否3D打印）；
##### 3月22~28号，整机测试，制定功能说明书；
