#### The is code snippet of operate AT24CXX EEPROM device use [virtual_i2c_for_stm32](https://github.com/GitYun/virtual_i2c_for_stm32.git)
---

##### Usage
- Declare `VirtualI2C` variable and check the I2C bus if exist AT24XX device:
	```C
	VirtualI2C_s g_sVirtualI2c = {
		{GPIOB, 10, 11},
		I2C_STANDARD_100KHz,
		0,
		i2cDelay
	};

	at24cxxCheck();
	...
	```

### If you have any suggestions or questions, please send an email to youneihai@126.com or youneihai@gmail.com