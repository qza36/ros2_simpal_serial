# ROS2简易的串口通信
- 通过订阅 ``/cmd_vel`` 话题，获得速度信息
- 通过串口`` /dev/ACM0``发送速度信息
## 已知问题
- 下位机向上位机发送数据时，若上位机未接收，下位机会一直发送，导致串口卡死，数据无法发送到下位机