# Thinkpad t460p opencore Big Sur

* This repo is based on : [T460PforMac](https://github.com/fhaoquan/T460PforMac)&&[Thinkpad-t460p-opencore](https://github.com/MAYDAY818/Thinkpad-t460p-opencore)
* 相关资料
- [一步一步从零迁移到OpenCore](https://heipg.cn/tutorial/example-of-from-clover-to-opencore.html)
- [黑苹果 OC 引导一键生成工具，可用于 CLOVER 转换成 OpenCore](https://vlambda.com/wz_5ioRxrCfszc.html)

- 目前屏幕亮度不能用,  使用SSDT-DGPU.aml 可以调节亮度, 但是会导致 HDMI & mini DP不能使用, 如果不外接屏幕, 勾选 SSDT-DGPU.aml 这个就可以了

- 一键开启HiDPI 外接屏幕超爽的 [one-key-hidpi](https://github.com/xzhih/one-key-hidpi)

## 🍺 Working:

| *项目*        | *工作与否*    |  *备注*  |
| --------   | -----:   | :----: |
| CPU变频        | √      |   14档, i7-6700HQ, 0x191b0000 |
| SMBios        | √      |   MBP13,3    |
| 🔊声卡        | √      |   ALC-293, alcid=28   |
| 显卡        | √      |   Intel HD530 @2k  |
| HDMI        | √      |  工作但不支持热拔插   |
| miniDP        | √      |  工作正常   |
| 有线网卡        | √      | Intel I219LM2      |
| WiFi        | √      |   BCM-94352z    |
| 蓝牙        | √      |       |
| 📹摄像头        | √      |       |
| USB-3.0        | √      |   速度：	最大 5 Gb/秒 |
| 🔋电池        | √      |       |
| 亮度快捷键       | √      |   F5,F6(Fn)    |
| 声音快捷键        | √      |   F2,F3    |
| 触摸板        | √      | 三指手势      |
| HIDPI        | √      |  2560x1440     |
| 睡眠💤唤醒        | √      |  🔌电源键     |
| 盒盖睡眠💤唤醒        | √      |       |
