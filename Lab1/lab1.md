# Lab 1

[Home](https://ece3400team19.github.io/)


## Description

In this lab, we used the various functionalities of the Arduino Uno and the Arduino IDE, as well as the GitHub repository.
We brainstormed and constructed a simple functional Arduino program using multiple external components and the Arduino Uno.
We then put together our robot and had it perform a [simple autonomous task](#robot-demo).

## Materials

* 1 Arduino Uno (in the box)
* 1 USB A/B cable (in the box)
* 1 Continuous rotation servos
* 1 Pushbutton
* 1 LED (any color except IR!)
* 1 Potentiometer
* Several resistors (kΩ range)
* 1 Solderless breadboard

## Part 1 - Modifying the Blink sketch

```
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```

<video controls="controls" width="800" height="600"
       name="Blinking" src="Lab1/blinking.mov></video>

Video of LED blinking.

![](Lab1/arduino.jpg)


## Part 2 - Using the analog output


## Part 3 - Using the Parallax servos

## Part 4 - Assembling the robot!

## Robot demo
