mpu9150
=======

A Python module for accessing the MPU-9150 digital accelerometer and gyroscope on a Raspberry Pi.

Example
-------

Assuming that the address of your MPU-9150 is 0x68, you can read read accelerometer data like this:

::

    >>> from mpu9150 import mpu9150

    >>> sensor = mpu9150(0x68)

    >>> accelerometer_data = sensor.get_accel_data()

Dependencies
------------

You need to have the ``python-smbus`` package installed.




