# ElectronicsClub_Himanshu_Meena_Task

Microcontroller Inputs, Outputs

System Overview and Inputs  
The main part of this electronic dice project is an Arduino Nano, which acts as the brain of the system and runs on a standard 5V supply. For physical input, the setup uses a  push button. This button is connected directly between one of the Arduino digital input pins and the circuit ground.  

System Outputs  
For the output the arduino uses seven digital pins to control seven individual leds. These leds are arranged on the physical board to visually like dice face. To prevent the components from burning out, each LED has a current-limiting resistor that keeps the operating current at a safe 15mA.  

How the Logic Works  
The operation of the dice is simple. When a user presses the button, it connects the input pin to ground, which the Arduino recognizes as a signal. After detecting the button press the microcontroller runs a routine to select a random number between 1 and 6. Based on the number it generates, the Arduino determines which combination of the seven output pins to activate. It turns on those selected pins, lighting up the corresponding LEDs to show the final result of the dice roll to the user.o display the final dice roll to the user.  
