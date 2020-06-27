
# ESP8266制作的鱼缸控制器（ESPHome版）

## 鱼缸控制器功能：
   1. 灯光、水泵等远程控制（MQTT);
   2. 水温过高保护；
   3. 底柜湿度控制；
   4. 定时功能；
   5. 喂食功能；
   6. 其他自定义功能。

##注意：
   1. NodeMCU的D8端口不可直接配置成Switch，需要配置成output类型才能作为输出之用，具体原因不详，可能随版本更新修复
   2. ESP8266启动时对某些GPIO口状态有要求，详见https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/
   3. 使用代码时需要修改wifi的ssid和password、MQTT的broker地址、用户名和密码