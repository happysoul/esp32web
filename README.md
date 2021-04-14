# esp32web

arduino 开发，使用了esp32存储中的1M-2M作为fs空间存储html等文件来显示页面

作为一个demo，做了几个简单功能，如果更新网页可以加入更多按钮来控制io扩展，主要是作为智能家居web控制抛砖引玉，提供个思路

参照8266版本修改了一份esp32的，传送门 https://github.com/happysoul/esp8266web 这里有部分截图

开发的时候 esp32-arduino 库没有esp8266完善，很多功能只有8266有，所以并不完整

#### 依赖
1、[ArduinoJSON](https://github.com/bblanchon/ArduinoJson)（项目-加载库-搜索ArduinoJSON并安装）更新此readme的时候版本是 6.17.3 老版本 5.x 的调用方法跟现在的版本区别很大，不兼容

2、[ESP32FS](https://github.com/me-no-dev/arduino-esp32fs-plugin) / [直接下载文件](https://github.com/me-no-dev/arduino-esp32fs-plugin/releases/download/1.0/ESP32FS-1.0.zip) 当前版本是1.0

