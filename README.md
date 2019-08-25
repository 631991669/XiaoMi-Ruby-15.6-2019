# XiaoMi-Ruby-15.6-2019 小米笔记本Ruby 15.6
## Hackintosh Clover files 黑苹果三叶草文件 
## [MI laptop Ruby 2019 (CN)](https://www.mi.com/mibook/ruby15-2019mx110/specs/)
## [Xiaomi Mi Notebook 15.6 Lite (RU)](https://market.yandex.ru/?suggest_text=Xiaomi%20Mi%20Notebook%2015.6%20Lite)

### 我的电脑配置 My computer configuration

| 规格     | 详细信息                                   							  	|
| -------- | -----------------------------------------------------------				|
| 电脑型号 Model  | 小米笔记本 Ruby 15.6" 2019款 独显款(UHD 620 + MX 110)      				|
| 处理器 Processer  | Intel(R) Core(TM) i5-8250U                      							|
| 内存 Memory  | SK hynix 16GB DDR4 2400MHz												|
| 硬盘 Disk  | KINGSTON MS80000058688  (238 GB)	M.2(SATA)								|
| 集成显卡 Integrated graphics  | Intel(R) UHD Graphics 620  (1 GB)          		|
| 内置显示器 Built-in display  | 中电熊猫 ID	NCP002A 1920x1080 IPS 15.6"					|
| 外接显示器 External display  | 1920x1080 							        		|
| 声卡     | Realtek ALC256 (M) (节点:13) 												|
| 网卡     | 无线：DW 1820A	有线：Realtek RTL 8168B				                		|
| 触控板   | I2C HID 																	|
| 照相机   | XiaoMi USB 2.0 WebCam 														|
| 读卡器   | Realtek USB 2.0 Card Reader 												|


## 介绍
所安装的系统版本为 10.14.6

### 2019年08月25日 更新
基于 [XenOriginal 的 EFI ](https://github.com/XenOriginal/XiaoMi-Ruby-15.6-UMA-only) 的基础上
修正了破音的问题，定制了USB接口补丁，更新了驱动，集成了DW1820A的驱动。
可能修正了直接连接4K显示器 ，外屏内屏 都黑屏的问题。（强制1080P）

## 注意事项
option 和 command 键位调换，（win 和 alt 键位调换）。


## 不能工作 Can not work
1. Built-in Speaker：内置扬声器


## 有小问题 Have little problem

1. Graphics 核显：启动时双屏显示 ,内屏不亮 {(关闭盖子再打开) 内屏显示正常}
2. Card reader 读卡器：  可能不会正常工作
