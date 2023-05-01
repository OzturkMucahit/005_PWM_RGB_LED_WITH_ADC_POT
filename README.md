# 005_PWM_RGB_LED_WITH_ADC_POT
Controlling with STM32F4 Discovery.

/*** Controlling RGB Led with ADC Unit.  ***/

For this project will be used;
 - 2 external buttons -> External buttons used with GPIOA Pin3 and GPIOA Pin5, 
 - 1 RGB LED and -> RGB led controlled by TIM1 timer.,
 - 1 500k potentiometer -> ADC used with ADC1.

** The value taken from the potentiometer processeded with the ADC unit and written to the each channel of the RGB LED.

When the system is start for the first time;
 - The settings of the colours in the RGB LED will be possible.
 - Switching between R-G-B colours quantities, by pushing button_1.
 
When the pushing button_2;
 - The adjusted R-G-B colours quantities will be set.
 - The RGB LED will not change even if the potentiometer is turned.

When the pushing both of the buttons (button_1 & button_2);
 - The settings of the colours in the RGB LED will be possible.
 - Switching between R-G-B colours quantities, by pushing button_1.
