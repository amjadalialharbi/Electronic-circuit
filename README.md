# Electronic-circuit
Connecting and programming an electronic circuit containing 6 servo motors using the (Tinkercad) simulation program.
## Electronic circuit programming code:

```
#include <Servo.h>

Servo myServo1, myServo2, myServo3, myServo4, myServo5, myServo6;

void setup() {
  myServo1.attach(8);
  myServo2.attach(9);
  myServo3.attach(10);
  myServo4.attach(11);
  myServo5.attach(12);
  myServo6.attach(13);
}

void loop() {
  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo1.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo1.write(pos);
    delay(15);
  }

  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo2.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo2.write(pos);
    delay(15);
  }

  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo3.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo3.write(pos);
    delay(15);
  }

  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo4.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo4.write(pos);
    delay(15);
  }

  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo5.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo5.write(pos);
    delay(15);
  }

  
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo6.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo6.write(pos);
    delay(15);
  }

  delay(2000); 
}
  ```
## Before operation :
![C1](https://github.com/amjadalialharbi/Electronic-circuit/assets/174282482/459e72e5-82e7-4b72-9f16-0777e194a396)

## After operation :
![C2](https://github.com/amjadalialharbi/Electronic-circuit/assets/174282482/3fcac1aa-7c7c-4755-b757-1e87292c1d90)
