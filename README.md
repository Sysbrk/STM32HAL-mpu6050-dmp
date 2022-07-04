# STM32HAL-mpu6050-dmp
dmp姿态解算获取角度和温度

在mpu6050.c文件中有关i2c的读写函数中的delay延时,要求延时时长比较小（代码中为hal_delay(1)）,或者直接注释掉.
