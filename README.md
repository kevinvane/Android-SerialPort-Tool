# Android-SerialPort-Tool
Android串口调试助手

根据[**https://github.com/licheedev/Android-SerialPort-API**](https://github.com/licheedev/Android-SerialPort-API)写的一个小工具，
没啥功能，基本也就用来调调控制板哪串口能用,发送一下简单的命令，
如果没懒癌发作的话，以后可能会加点最近命令保存啥的功能。


加载命令列表只支持这种格式
```
AABBCCDDEEFF // 命令注释
```

![1](./pics/1.png)

![2](./pics/2.png)


## 依赖
```
implementation 'com.github.licheedev.Android-SerialPort-API:serialport:1.0.1'
```