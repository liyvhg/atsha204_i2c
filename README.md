# atsha204_i2c
Arduino Library for Atmel CryptoAuthentication ATSHA204A chip

This project is based on https://github.com/sparkfun/SparkFun_ATSHA204_Arduino_Library .  
The SparkFun version is SWI (Single Wire Interface ).  
This version is I2C interface.  
Mainly tested on Arduino core for ESP8266 2.3.0 environment.

I have added some simple function to get chip id and calculate mac.  

You can init the chip using hashlet on raspberry pi : https://github.com/cryptotronix/hashlet  

There is a test_atsha204a_mac.js to verify the mac result.

Attention Please: we need to set BUFFER_LENGTH to at least 64 in Wire.h 
