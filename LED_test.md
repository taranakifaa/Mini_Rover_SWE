## Let's program our first component

First lets install a python program: 
```bash
sudo apt-get install python-rpi.gpio python3-rpi.gpio
```
Now in order to start programming we are going to do this command: 
```bash
nano Blinking_LED_test.py
```
Now the command 'nano' brings you to a terminal based text editor: 
Let's try this software only code to demonstrate the idea of what we want our LED to do:
```py
import time

while True:
print("Hello")
time.sleep(1)
print("Hello")
time.sleep(1)
```
Once you type this out to save our code and leave the text editor: 
```bash
CTRL + O , ENTER , CTRL + X
```
How do you run the code? Here's how: 
```bash
python3 Blinking_LED_test.py
```
You should see this: 

 <img width="496" height="372" alt="image" src="https://github.com/user-attachments/assets/9d2e1b27-6b37-4665-9402-831f4287c398" />

```py
import RPi.GPIO as GPIO  # Library used to control the Raspberry Pi GPIO pins
import time              # Used to create time delays

LED_PIN = 17  # Defining which GPIO pin we want to use (GPIO 17)

GPIO.setmode(GPIO.BCM)        # Use the GPIO/BCM pin numbering system
GPIO.setup(LED_PIN, GPIO.OUT) # Set GPIO 17 as an output pin

while True:  # Run this program forever

    GPIO.output(LED_PIN, GPIO.HIGH)  # Set GPIO 17 HIGH (turn LED on)
    time.sleep(1)                    # Leave LED on for 1 second

    GPIO.output(LED_PIN, GPIO.LOW)   # Set GPIO 17 LOW (turn LED off)
    time.sleep(1)                    # Leave LED off for 1 second
```
Now let's try another type of LED to demonstrate TWO GPIO ports 
```python

import RPi.GPIO as GPIO # defining that we are accessing our GPIO port
import time # time commands

LED1 =17
LED2 =27
LED3 =22

GPIO.setmode(GPIO.BCM)
GPIO.setup(LED1, GPIO.OUT)
GPIO.setup(LED2, GPIO.OUT)
GPIO.setup(LED3, GPIO.OUT)

LED_RED = 17 # Activating GPIO PIN 17
LED_BLUE = 27 # Activating GPIO PIN 27
LED_GREEN = 22 # Activating GPIO PIN 22

#cycle through the colors, this cycling is called a FSM 
while True: # run this forever
time.sleep(1)
GPIO.output(17, GPIO.LOW)
GPIO.output(27, GPIO.HIGH)
time.sleep(1)
GPIO.output(27, GPIO.LOW)
GPIO.output(22, GPIO.HIGH)
time.sleep(1)
GPIO.output(22, GPIO.LOW)
GPIO.output(17, GPIO.HIGH)
time.sleep(1)

```
Now assuming you may not have the components bought we can still demonstrate without hardware: 
```python
int main()

array[] = {a,b,c}

while(1){
for(int i = 0, i > 2, i++){
cout >> [i] >> endln;
}
}


```

Similarly you can do this without an LED to see the behavior:
<img width="1483" height="215" alt="image" src="https://github.com/user-attachments/assets/baaee14e-bc09-4feb-8d8f-de4f673eadda" />

Let's connect our LED like this:
<img width="1764" height="1338" alt="image" src="https://github.com/user-attachments/assets/eef028ec-defa-43e0-be8c-5ed0815244fd" />
