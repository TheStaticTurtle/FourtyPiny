# FourtyPiny
This project is a simple i2c 40 pin GPIO expander module based on the PCA9505 or the PCA9506.

<img src="https://user-images.githubusercontent.com/17061996/116939281-61ab6500-ac6c-11eb-8e89-9911f779173d.png" height="200"/>

The module is designed for daisychaining to support up to 8 modules giving a total of 320 GPIO, if you want to go further you might be able to use an other i2c port or an i2c switch giving pretty much infinite IO

# Hardware
It was designed under EasyEDA.

The module doesn't include pullups so be sure which chip you use, The PCA9505 has pullups the PCA9506 does not!



## Software
Multiple libraries exist for this chip:
Language | Link
---------|------
Arduino Library | https://github.com/tofuman0/PCA9505_06
Circuitpython class |  https://github.com/TheStaticTurtle/CircuitPython_PCA9505
