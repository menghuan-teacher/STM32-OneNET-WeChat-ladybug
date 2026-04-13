# STM32-OneNET-WeChat-ladybug
STM32+微信小程序连接onenet云平台

## 📦 工程获取
本项目完整源码已打包为 `ladybug.zip`，包含：
- `wifi_optimize_demo/`：STM32 硬件工程（MQTT连接OneNET云平台）
- `FuLi/`：微信小程序工程（设备数据展示与远程控制）
- 硬件接线+云平台物模型表格

### 下载使用
1.  直接下载 `ladybug.zip` 压缩包
2.  解压后得到完整工程文件夹
3.  STM32工程使用vscode打开编译，小程序使用微信开发者工具打开。
4.  STM32硬件工程修改esp8266.h文件中的wifi名称/密码，三元组
5.  微信小程序工程修改index.js的三元组
