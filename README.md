MultiWii-Firmware v2.0 - DCwii edition
=====

**Disclaimer**     
At now my Firmware is staying in testing condition! All the actions you perform at your own risk!

**This is a fork of the original MultiWii**     
Original MultiWii GitHub page: https://github.com/multiwii/multiwii-firmware     
Original MultiWii v2.0: http://code.google.com/p/multiwii/downloads/list file name: "MultiWii_2_0.zip"     
     
**This firmware writed for my project DCwii:**     
https://github.com/geovas/DCwii     

**New Features:**
- Work with Arduino Pro Mini 8MHz 3.3v
- Work with DC-motors (just like in WLtoys V949/V929)
- DC-motors can fully stopped
- Work with Gyro MPU-3050 (you can get it from WLtoys V949 for example)
     
**My settings:**     
- #define QUADX
- #define MINCOMMAND 1000
- #define MINTHROTTLE 1050
- #define MAXTHROTTLE 2000
- #define MIDRC 1500
- #define DEADBAND 8
- #define EXT_MOTOR_RANGE
- #define I2C_SPEED 400000L
- #define MPU3050
- #define MPU3050_LPF_20HZ
- #define GYRO_ORIENTATION(X, Y, Z) {gyroADC[ROLL] = Y; gyroADC[PITCH] = -X; gyroADC[YAW] = -Z;}
     
**My quadcopter spec-list:**
- Platform: WLtoys V949 BNF
- MCU: Arduino Pro Mini 8MHz 3.3v
- Gyro: MPU-3050
- Tx/Rx: Turnigy 6XS FHSS / RX7000S
- LiPo: Turnigy Nano-Tech 600mAh 1S
- Misc: Turnigy Voltage Booster for Servo