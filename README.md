# Hackintosh-OC-Optiplex-5060MFF

## 平台配置
* 准系统：Dell Optiplex 5060 Micro
* CPU：Intel Core i5-8600T (Coffee Lake)
* GPU：Intel UHD Graphics 630
* 网卡：Apple BCM94360CS2
* 内存：16GB DDR4 2666MHz

## 特性
* 仿冒机型：Macmini8,1（SN已去除，需自行补充）
* 系统版本：Big Sur 11.2.3
* 显示正常，显卡FB：3E9B0007，VRAM：1536MB
* 内置扬声器正常，前置耳机输出正常，声卡ID：11
* WiFi正常，免驱
* 蓝牙正常，支持接力，支持随航
* 睡眠正常，支持电能小憩
* USB端口正常，端口属性正确修正
* EC（SMC）正常，支持风扇转速报告
* CPU电源管理正常，支持功率报告
* 支持开机音效

## 已知问题
* 电源按钮不工作
* 内置麦克风不工作

## BIOS配置（版本：1.9.1）
* 恢复出厂设置：Load Defaults（但更加推荐使用主板CMOS跳线进行完全复位）
* 关闭VT-d
* 关闭CFG Lock：0x5BE 0x0
* 设置64M预分配显存：0x8DC 0x2

## 更新日志
###2021-3-20
* 更新OpenCore 0.6.7
