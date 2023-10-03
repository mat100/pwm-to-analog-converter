# Opto isolated PWM to Analog (0-5V) converter module
For my project of converting a manual lathe to CNC, I was looking for a galvanically isolated PWM to analog signal converter (0-5V). This converter replaces the manual potentiometer for regulating the spindle speed. The potentiometer for spindle speed regulation on most Chinese lathes operates as a voltage divider in the range of 0-5V. Unfortunately, this voltage is not galvanically isolated, and more than 100V voltage can be measured against the ground, which is life-threatening. On the internet, I found several converters, but most of them are PWM to 0-10V with a requirement of 12V power supply and without galvanic isolation. This converter can work with an input signal of 3.3V and 5V. The output operates within the range of the supply voltage, in this case, therefore 0-5V.

![image](https://github.com/mat100/pwm-to-analog-converter/assets/3736719/16ba30e9-50a0-4acd-9e5b-2cae6d1e3ced)

![image](https://github.com/mat100/pwm-to-analog-converter/assets/3736719/6e14126d-159c-41f6-bc7a-3a5696f20f2c)

