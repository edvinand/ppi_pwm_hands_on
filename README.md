# ppi_pwm_hands_on

In this hands-on we want to explore the PPI of the nRF52. This sample is pretty much "hardcoded" for the nRF52840dk_nrf52840, but if you want to run it on another nRF52xxx device, all you should need to do is to change these definitions on line 29 in main.c:

```C
#define LED_1   13  // From the description on the back of the DK
#define LED_2   14  // From the description on the back of the DK
#define LED_3   15  // From the description on the back of the DK
#define LED_4   16  // From the description on the back of the DK
```

The project should compile without changes. By default it should use the PWM signal generated to "breathe" with LED1. Your job is to add the other LEDs to the mix.
The instructions are found in main.c. Look for this line to get started:

```C
//  STEP 1: Implement a method for initializing PWM channel 1, for a total of 2 individual PWM channels
```
