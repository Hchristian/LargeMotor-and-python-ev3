# LargeMotor-and-python-ev3
Problem with LargeMotor on ev3-ev3dev- jessie 2015-12-30
>>> import ev3
>>> from ev3 import lego
>>> from ev3.lego import LargeMotor
>>> Left=LargeMotor('outA')
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
File "build/bdist.linux-armv5tejl/egg/ev3/lego.py", line 211, in __init__
File "build/bdist.linux-armv5tejl/egg/ev3/ev3dev.py", line 334, in __init__
ev3.ev3dev.NoSuchMotorError: No such motor port=outA type=lego-ev3-l-motor
