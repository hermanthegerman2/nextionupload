# nextion

Python script to upload to an nextion display via USB TTL connected on a raspberry pi

Original: Python Upload script (historic), Björn Schrader

See: http://support.iteadstudio.com/support/discussions/topics/11000007783

My small modification to support my nextion display connected on doorpi

This version can upload a tft file to a nextion display connected on rasperry pi via USB-TTL

Aufruf

Quellcode
$ python nextionupload.py nextiondisplaycode.tft


Port wird definiert in nextionupload.py

Quellcode
PORT = '/dev/ttyUSB0'
BAUDCOMM = 9600
BAUDUPLOAD = 115200
