[![ MMC3316xMT](MMC3316xMT_I2C.png)](https://store.ncd.io/product/mmc3316xmt-%C2%B116-gauss-3-axis-magnetic-sensor-i2c-mini-module/).

#  MMC3316xMT

The MMC3316xMT is a 3-axis magnetic sensor with on-chip signal processing.This device can measure magnetic fields within the full scale range of ±16 Gauss with heading accuracies of 1°.
This Device is available from www.ncd.io 

[SKU: MMC3316xMT]

(https://store.ncd.io/product/mmc3316xmt-%C2%B116-gauss-3-axis-magnetic-sensor-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MMC3316xMT 3Axis magnetic sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mmc3316xmt-%C2%B116-gauss-3-axis-magnetic-sensor-i2c-mini-module/">MMC3316xMT 3Axis magnetic sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MMC3316xMT.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
