---
sort: 3
---

# MAX30102_BLE

```
本程序相较于MAX30102.ino增加了BLE数据传输功能
此前操作步骤请参考MAX30102文档
```

BLE功能部分介绍

1. 在手机端安装”ESP32 Sensor Kit“软件，并给予其获取位置信息，使用蓝牙、WIFI等系统权限

4. 点击“BLE接入”按钮

   <img decoding="async" src="https://addison-cq.github.io/webPages/images/Screenshot_20221111_123302_com.example.esp32sensorkit_f.jpg" width="20%">

5. 此时APP将自动连接开发板

   <img decoding="async" src="https://addison-cq.github.io/webPages/images/Screenshot_20221208_171005_com.example.esp32senso.jpg" width="20%">
   
6. 若APP未能成功连接开发板，请先点击APP连接按钮，再按压一次开发板RST按键，就行重新尝试

   <img decoding="async" src="https://addison-cq.github.io/webPages/images/Screenshot_20221208_172530_com.example.esp32senso.jpg" width="20%">
   
6. 稍等片刻，APP与开发板成功连接，此时我们可以通过APP查看开发板测算出的心率与血氧浓度数据

   <img decoding="async" src="https://addison-cq.github.io/webPages/images/Screenshot_20221208_174837_com.example.esp32senso.jpg" width="20%">