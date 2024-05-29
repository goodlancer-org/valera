How to install Linux on eMMC
================================

Before we start
~~~~~~~~~~~~~~~~~

If you don't have a Linux installed on your eMMC you can install one manually.
You will need for this:

#. eMMC card to install Linux to 
#. eMMC-microSD adapter 
#. microSD-USB adapter to plug everything into the PC 
#. Software to flash the eMMC card, i.e. balenaEtcher

Step 1. Download Linux image
~~~~~~~~~~~~~~~

It's better to take an image from the microcomputer manufacturer website, in case of Orange Pi -
from http://www.orangepi.org/html/serviceAndSupport/index.html

3rd party distributions might be more feature rich or performant, but might be leaking some
drivers, i.e. i2c overlays, so in most cases it's safer to stay with Linux distributions 
provided by the microcomputer manufacturer.

In this example we will go with Ubuntu.

Step 2. Flash eMMC with Linux image
~~~~~~~~~~~~~~~


Step 3. Enable i2c in Linux settings
~~~~~~~~~~~~~~~

Use sudo ``orangepi-config`` to enable i2c on the computer how it's 
described on http://www.orangepi.org/orangepiwiki/index.php/Orange_Pi_3B#40pin_I2C_test_2