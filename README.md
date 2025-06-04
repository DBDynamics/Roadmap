# Roadmap
⭐ 欢迎查看DBD最新的产品路线

## 电机驱动器

### Ant系列
- Ant4
  - CAN通信
  - 板载USB
  - 120个节点
  - 中小功率 42及以下
  - [Github链接](https://github.com/DBDynamics/Ant)
  - [Gitee链接](https://gitee.com/DBDynamics/Ant)
- Ant6
  - 隔离CAN通信
  - 取消板载USB
  - 其他保持不变
  - [Github链接](https://github.com/DBDynamics/Ant6)
  - [Gitee链接](https://gitee.com/DBDynamics/Ant6)

### Bee系列
- Bee
  - 适配大功率 57及以上 
  - 精简设计 极小体积
  - 开环电机
  - 单回零传感器
  - 尺寸紧凑 极简设计
  - [Github链接](https://github.com/DBDynamics/Bee)
  - [Gitee链接](https://gitee.com/DBDynamics/Bee)

- Bee2  
  - 适配大功率 57及以上
  - 支持闭环步进电机
  - 支持正负限位
  - 隔离通信 更稳定
  - 大号端子 方便施工
  - [Github链接](https://github.com/DBDynamics/Bee2)
  - [Gitee链接](https://gitee.com/DBDynamics/Bee2)
  
### Tiger
- 3相无刷电机控制器
- 支持霍尔
- 支持编码器
- FOC控制
- 适配250W
- [Github链接](https://github.com/DBDynamics/Tiger)
- [Gitee链接](https://gitee.com/DBDynamics/Tiger)

## 一体电机
- BeeS步进伺服
  - 超级紧凑 体积小
  - 隔离总线通信 稳定高效 
  - 目前有三个型号 28 42 57
  - 支持正负限位
  - [Github链接](https://github.com/DBDynamics/BeeS)
  - [Gitee链接](https://gitee.com/DBDynamics/BeeS)

- Bull无刷伺服
  - 低压无刷减速一体伺服电机
  - 力矩持续4N.m 最大15N.m
  - [Github链接](https://github.com/DBDynamics/Bull)
  - [Gitee链接](https://gitee.com/DBDynamics/Bull)


## IO模块
- BeeOut
  - 16路IO输出模块
  - 隔离通信
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
- BeeIn
  - 16路IO输入模块
  - 隔离通信
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
## LED光源
- BeeLED
  - 4通道
  - 电流闭环控制  
  - 12/24V供电
  - 隔离通信
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
## 脉冲控制器
- BeePulse2
  - 脉冲+方向控制
  - 隔离通信
  - 正负限位
  - 激光PWM控制
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
## 调试器/控制器
- USB485
  - 方便插电脑调试
  - 点位运动
  - 8轴同步插补运动
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
  
- PyV3s
  - 可以Python编程的极简Linux控制器
  - 板载贴片焊接TF卡
  - 扩展接口丰富 (具有Python接口和使用例程)
    - IO输入 x4
    - IO输出 x4
    - TTL UART x3
      - 可扩展RS485
      - 可接串口热敏打印机
      - 可接串口传感器 如陀螺仪 超声波
      - 可以接串口屏幕
    - USB x1
      - 可接USB热敏打印机
      - 可接USB串口
    - 以太网 x1
      - 可接路由器
      - 可接4g网络模块 实现远程登录
    - 正交编码器 x1
      - 可接手轮
    - RS485(硬件加速@250kbps/500kbps) x2
      - 支持32/64轴点位运动
      - 支持2/64轴同步插补运动
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)
   
- PyH6Pro
  - 4核Cotex-A57 2G内存 
  - Linux Ubuntu操作系统
  - 支持256/512轴点位运动
  - 支持256/512轴同步插补运动
  - [Github链接](https://github.com/DBDynamics/)
  - [Gitee链接](https://gitee.com/DBDynamics/)