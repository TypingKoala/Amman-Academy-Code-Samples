# Button Record
This challenge lab will guide you through creating an Arduino circuit that will be able to record the number of button presses you make and play them back to you on an LED. There are two buttons, the *record button* and the *count button*. There are also two LEDs, the *recording LED* and the *flash LED*.

## Expected Behavior
When holding down the *record button*, a red *recording LED* will light up and the Arduino will begin recording the number of button presses to the *count* button. If you press the count button three times then release the record button, the red recording light will turn off, and the *flash LED* will then flash 3 times (turning on for 500ms and turning off for 500ms for 3 iterations). You can then repeat the process by holding down the *record button*.

## Instructions
We recommend setting the following PIN assignments, but it is ultimately up to you.

* Record button: HIGH on pin 2 when depressed
* Count button: HIGH on pin 3 when depressed
* Flash LED: output on pin 13
* Record LED: output on pin 12

The following instructions will help you slowly build up your Arduino programs.

1. Create variables at the beginning of the program assigning the pin numbers of the buttons and LEDs to helpful names (such as *flash_led_pin*, *record_led_pin*, *count_button_pin*, and *record_button_pin*)
2. Initialize variables that will store the state of the circuit. You will need one that stores the state of the record state, the number of flashes, and anything else you might want to keep track of.

#todo