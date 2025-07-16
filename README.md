This project contains 3 main modules :

GSM A6 Module - This is module is responsible for Making/Receiving Calls and SMS.
LCD 16x02 Display - To see the output
Hex Keypad - To give input
The STM32F407 MCU controls the GSM A6, LCD, and Keypad. So to make programming simple and organized, I developed individual driver code for Interfacing GSM A6 module, LCD and Keypad on STM32F407 MCU. Then I simply included these driver files in the main program and called respective APIs. You can find these driver codes in the Supplies below.
