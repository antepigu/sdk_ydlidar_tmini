# 硬件FAQs：
### YDLIDAR雷达需要什么硬件支持？
* 芯片主频大于30MHz.
* 如果芯片主频太低，　数据不能实时解析，数据将会丢失，一些角度范围会丢失，比如:Arduino UNO(16 MHz).
* 推荐最小主频大于30MHz才能实时解析雷达数据，如果是TG30这种采样率20K，　需更高的主频．
* YDLidar-SDK 不支持控制器芯片，如STM32, Arduino.

## YDLIDAR雷达可以在什么样的开发板上使用？
* 雷达采样率小于6K的，开发板主频大于30MHz就可以．
* 更改采样率雷达，开发板主频大于100MHz.

## YDLidar-SDK支持哪些雷达型号？
YDLidar-SDK 支持现有所有EAI标品雷达，定制版本请联系EAI
