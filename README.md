**Name:** NIKITA GUDE                                                                                                                                                          
**Company:** CODETECH IT SOLUTIONS                                                                                                                                                  
**ID:** CT4ES2571                                                                                                                                                               
**Domain:** EMBEDDED SYSTEMS                                                                                                                                                  
 **Duration:** JUNE 20th,2024 to JULY 20th, 2024                                                                                                                                 
 **Mentor:** MUHAMMED MUZAMMIL AHMED


## OVERVIEW OF THE PROJECT

#### LED BLINKING WITH ARDUINO

### OBJECTIVE:
The objective of this project is to program an arduino board to blink an LED at a specific interval. This project introduces basic embedded programmming concepts and interfacing with hardware.

### Hardware Required:

1 X LED                                                                                                                                                                                   
 1 X Resistor, 330 Ohm                                                                                                                                                             
Breadboard                                                                                                                                                                          
 Arduino UNO R4 or earlier versions.

### Hardware Description:

1 X LED: We are controlling only one LED in this program.

1 X Resistor, 220 Ohm: For every LED, we need one current limiting resistor.

Breadboard: A breadboard is a fundamental tool used in electronics and prototyping to build and test circuits without soldering.

Jumper wires: Jumper wires are simple electrical wires with connectors on both ends used to create connections between various electronic components or points on a circuit on a breadboard.

### CIRCUIT:
Connect one end of the resistor to the digital pin correspondent to the led_pin constant. Connect the long leg of the LED (the positive leg, called the anode) to the other end of the resistor. Connect the short leg of the LED (the negative leg, called the cathode) to the GND. In the diagram below we show an UNO board that has D8 as the led_pin value.


![ckt](https://github.com/Nikk1729/CODETECH-Task1/assets/123321525/aa764ef9-1b4d-463e-8e57-046664e7c7d2)

The value of the resistor in series with the LED may be of a different value than 220 ohms; the LED will light up also with values up to 1K ohm.

### Arduino Code:


#define led_pin 8                                                                                                                                                                      
void setup() {                                                                                                                                                                           
// We're going to write to the pin, so we set its mode to OUTPUT                                                                                                           
    
    pinMode(led_pin, OUTPUT);
    
    }
    
void loop() {                                                                                                                                                  
    digitalWrite(led_pin,HIGH); // Turn the LED on                                                                                                                             
    delay(1000); // wait a second                                                                                                                                
    digitalWrite(led_pin,LOW); // Turn the LED ofF                                                                                                                             
    delay(1000); // wait a second
    
    }

### Deployment Using Arduino IDE:
![image](https://github.com/Nikk1729/CODETECH-Task1/assets/123321525/f1881768-d44e-4f15-8615-2306c25fceb1)

### RESULTS:


![BLINK](https://github.com/Nikk1729/CODETECH-Task1/assets/123321525/b164aa6b-d159-4423-9a76-27991e527e4b)

