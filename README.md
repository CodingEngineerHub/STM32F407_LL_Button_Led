# STM32F407_LL_Button_Led

This project contains simple low level code example.When you push the user button 4 leds light.
in my STM microcontroller user button connect to PA0  and leds connect TO PD12, PD13, PD14, PD15
firstly we have to open ports' RCC and set mode of these ports   
you just change main.c file.
![image](https://user-images.githubusercontent.com/75130493/147403192-92d707b0-8c78-42b2-9b3d-8adf7f37b9cf.png)

in infinite loop when you press the user button will turn on otherwise led will turn off
![image](https://user-images.githubusercontent.com/75130493/147403263-5bbaf5fb-6008-4fcd-8d96-b5e823e9bf14.png)




