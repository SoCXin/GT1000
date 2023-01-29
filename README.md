# [GT1000](https://doc.soc.xin/GT1000)

* [GiantSemi](https://www.giantsemi.com/): [Cortex-M0+](https://github.com/SoCXin/Cortex)
* [L1R1](https://github.com/SoCXin/Level): ? MHz

## [简介](https://github.com/SoCXin/GT1000/wiki)

[GT1000](https://www.giantsemi.com/cp)为全功能、全集成的 UWB 系统级芯片，包含了射频、模拟、基带、协议、软件和嵌入式MCU。

### 关键参数

* 支持最新的IEEE802.15.4、802.15.4z 以及 FiRa标准
* 单芯片一发三收（1T3R）架构，支持2D和3D AoA（到达角度）
* 支持4.0 ~ 9.0GHz频率范围
* 支持多种标准通信速率31.2Mbps, 27.2Mbps, 7.8Mbps, 6.8Mbps和850Kbps
* 集成MCU, 主频最高为124.8MHz，拥有丰富的SRAM和Flash资源
* 集成协议和软件，无需在外面的处理器上运行协议或软件
* 丰富的接口SPI、I2C、UART、GPIO
* 支持基于飞行时间（ToF）的单边、双边双向测距；支持AoA测量；支持到达时间差（TDoA）测量
* 接收灵敏度 -94dBm@6.8Mbps, -103dBm@850Kbps
* 测距精度为±6厘米，AoA测量精度为±3度

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/GT1000)

该芯片于2022年9月开始批量出货，目前还没有开发板资源。

[GT1000](https://www.giantsemi.com/cp)实现了极低功耗，接收功耗的峰值仅为71mW，发射功耗的峰值仅为37mW, 深度睡眠模式电流仅为0.8µA。相比目前市场上的UWB方案，GT1000的功耗得到了极大幅度的降低，非常有利于以电池供电的UWB终端产品。由于UWB最高通信速率是低功耗蓝牙的接近16倍，以每Mbps计算的功耗，GT1000的功耗已经处于和低功耗蓝牙相当甚至更低的水平。

GT1000采用单芯片一发三收的收发机架构，非常有利于实现低成本的3D AoA方案。目前市场上的UWB方案可能需要使用两颗UWB芯片或者复杂的射频前端元件（比如射频开关）才能实现3D AoA。GT1000单芯片即能支持3D AoA, 并且射频前端元件非常简单，BoM成本得到大幅降低。

UWB 提供了高度可靠、安全、精确、快速和高能效的测距和定位能力，其测距和定位不依赖于任何外在的基础设施，并且室外、室内皆可。同时，UWB也提供了通信速率可配的无线连接。UWB正在手机、可穿戴设备、智能家居、标签、定位器、数字钥匙、智慧门禁、支付、工商业室内定位、智慧城市等无处不在的应用场景中发挥越来越大的作用。UWB正在全球范围内为个人生活、工商业活动提供便捷、舒适和高效。

## [www.SoC.xin](http://www.SoC.Xin)
