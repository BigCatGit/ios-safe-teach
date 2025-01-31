# 大猫iOS逆向与安全暑假班



## 老师简介

```
从事ios与c++逆向10余年, 参与过10多个热闹大型app的安全分析与项目开发，以及pc端游戏驱动保护与辅助功能开发、C/S、B/S等模式的系统独立开发等等工作。
```



## 职位方向

```
热门app都需要大量的前后端安全工程师等职位对自主研发的app等进行自身漏洞分析与保护，以及同行竞品分析等。
```



# 附言

```
中级进修完成的同学，赠送老师在安全维护过程中自主开发的新机软件与自动化脚本软件、内存搜索小工具等完全代码。
```



# 法律声明

```
本课程传授的所有技能与工具、以及思路等所有内容，都只为提升app自身安全，希望大家学了过后都可以为净化网络环境，提升网络安全出一份力，禁止任何人用于非法途径，否则后果自付，与教程团队无关。
```



# 初级篇



## 第1章	背景知识

### 1.1 iOS逆向与安全简介

```
UI结构分析、几大热门app功能实现分析、app与系统底层运行机制与原理讲解、动态调试与静态调试深入讲解、frida动态调试脚本开发让分析事半功倍、反调试与反调试对抗、反越狱与反越狱对抗、实战修改设备信息实现新机软件、实战自动化脚本软件原理逆向与开发、实战逆向app纯协议与对抗、ios结合golang实现游戏内存搜索器。
```



### 1.2 iOS越狱平台简介



## 第2章	环境搭建

### 2.1 正向开发环境搭建

### 2.2 越狱环境搭建

- iPhone手机越狱
- ssh连接越狱手机配置
- theos环境配置
- MonkeyDev环境配置
- mac下ida安装以及使用
- win10下ida安装以及的使用
- otools命令的使用
- class-dump命令的使用
- lipo命令的使用
- frida安装和使用
- frida砸壳环境安装和使用
- fsmon-ios安装和使用
- CrackerXI+砸壳环境搭建和使用

​	

## 第3章	逆向基础

### 3.1 认识Mach-O文件格式

### 3.2 ARM汇编基础

### 3.3 inline hook

### 3.4 iat hook 和 eat hook

### 3.5 fishhook、dobby(hookzz)汇编hook库

### 3.6 tweak hook oc和c++函数实现

### 3.7 MonkeyDev hook函数实现

### 3.8 MonkeyDev反反调试检测

### 3.9 代码实现类int3断点



## 第4章	动态分析

### 4.1 认识lldb调试器

### 4.2 lldb常用命令

### 4.3 实战lldb调试器调试自己的app

- 函数符号断点
- c++异常断点
- 内存读写断点

### 4.4 实战lldb调试器调试第三方app

- 认识ALSR和内存地址
- 函数符号断点
- 内存读写断点
- 条件断点
- 实战lldb常用命令
- 实战app按钮控件响应事件跟踪
- 实战获取app的keychain数据 
- 实现自定义ldb命令提升分析效率



## 第5章	静态分析

### 5.1 认识IDA反汇编工具

### 5.2 IDA定位app关键字符串

### 5.3 IDA配合lldb分析app功能实现

### 5.4 IDA修复分析错误的参数和函数体

### 5.5 IDA分析结构体



## 第6章	Firda实战

### 6.1 nodejs入门

### 6.2 frida附加三方app并加载脚本

### 6.3 开发Frida脚本实现oc函数监控

### 6.4 开发Frida脚本实现c++函数监控

### 6.5 开发Frida脚本实现app访问文件监控

### 6.6 开发Frida脚本实现app获取设备信息监控

# 中级篇(实战篇)



## 第7章 安全分析实战

### 7.1 反调试、反反调试实现与对抗

### 7.2 反越狱、反反越狱实现与对抗

### 7.3 VPN检测与对抗

### 7.4 sim卡识别工作机与对抗

### 7.5 应用签名篡改与对抗

### 7.6 动态库注入检测与对抗

### 7.7 inline hook的检测与对抗

### 7.8 iat hook的检测与对抗

### 7.9 汇编指令篡改对抗



## 第8章 实战新机软件实现与对抗

### 8.1 认识新机软件

### 8.2 设备唯一id修改

### 8.3 生成网卡信息

### 8.4 生成4G与wifi网络

### 8.5 反反越狱开发

### 8.6 生成系统设备信息

- 生成IDVA和IDFA
- 生成ICCID与序列号
- 生成UserAgent
- 生成设存大小
- 生成硬盘大小
- 生成cpu核心数
- 生成系统版本
- 生成系统所有者名字
- 生成传感器数据
- 生成重力计数据
- 生成陀螺仪数据
- 生成电量
- 修复指纹设备为可用
- 生成系统运行时间
- 生成app文档路径
- 生成app安装路径

### 8.7 进程间通信

### 8.8 隐藏VPN

### 8.9 GPS伪装与转换

### 8.10 SpringBoard信息修改

- 生成4G与wifi网络图标
- 修改电量图标
- 隐藏VPN图标

### 8.11 生成app原有签名

### 8.12 app授权实现

### 8.13 deb重打包

### 8.14 使用ollvm混淆打包

### 8.15 对抗新机软件



## 第9章 自动脚本软件实现与对抗

### 9.1 逆向某键精灵配合三方库实模拟现点击功能

### 9.2 图片查找

### 9.3 颜色查找

### 9.4 文件查找

### 9.5 模拟按键功能

### 9.6 Toast实现

### 9.7 脚本软件架构搭建

### 9.8 脚本实现使用javascript作为开发语言

### 9.9 脚本自定义函数实现控制设备

### 9.10 创建自己的脚本文件加密格式

### 9.11 app管理脚本文件

### 9.12 app授权管理与打包

### 9.13 对抗脚本软件的非真实用户行为



## 第10章 纯协议实战与对抗

### 10.1 http协议抓包利器Charles的使用

### 10.2 TCP/IP抓包利器Wireshark的简介

### 10.3 分析xx令app发送请求接口

### 10.4 分析xx令app的http协议接口参数

### 10.5 分析xx令app的http协议加密参数

### 10.6 使用nodejs或者golang实现协议接口

- 获取手机验证码
- 手机号登录
- 检查xx令状态
- 绑定账号并激活xx令
- 绑定游戏账号
- 解绑游戏账号
- 创建订单
- 查询订单
- 查询余额
- 获取个人信息
- 批量获取手机号
- 批量获取未激活的xx令
- 批量订单

### 10.7 对抗协议破解






