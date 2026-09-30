## Let's program our first component

First lets install a python program: 
```bash
sudo apt-get install python-rpi.gpio python3-rpi.gpio
```
Now in order to start programming we are going to do this command: 
```bash
nano Blinking_LED_test.py
```

```py
import RPi.GPIO as GPIO # we are defining our RPI pins 
import time #real time 
LED_PIN = 17 #defining which pin we want to set to high (GPIO 17) see data sheet to know which pins

while True: # run this program forever
GPIO.output(17, GPIO.HIGH) #set GPIO 17 to high (turn on led)
time.sleep(1) #leave the HIGH set on for one second 
GPIO.output(17, GPIO.LOW) #set GPIO 17 to low (turn off led)
time.sleep(1) #leave the LOW state on for one second

```

Similarly you can do this without an LED to see the behavior:
<img width="1483" height="215" alt="image" src="https://github.com/user-attachments/assets/baaee14e-bc09-4feb-8d8f-de4f673eadda" />

Let's connect our LED like this:
<img width="1764" height="1338" alt="image" src="https://github.com/user-attachments/assets/eef028ec-defa-43e0-be8c-5ed0815244fd" />
