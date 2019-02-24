# Spectral Clock

## About 
Spectral clock is a device which consist of a bar with over a dozen of leds attached to it and motor which accelerates the bar to quite huge speed. Leds are controlled by the microcontroller and when the motor speed is big enough switching off and on the leds in strictly defined moments results in continues image. The image is just an impression, because the human eye is unable to notice the differences or the changes in objects which oscillates more than 20Hz. Taking above into consideration 1200 turns the engine per minute results in a pure continues image. Lets say in simpliest example one led will be switched on all the time. Then observer will see the circle. Imagine what will happen if microcontroller calculate the time of ratio and basing on that time the half of it turn on the led and the second turn off. Then he'll see a half of the circle. Because of huge microcontroller computing power leds can be turned off and on whenever the constructor or programmer wants, so it is possible to display quite sophisticated pictures like this one below.

**To find out more, please check out the [spectral clock wiki][wiki].**

## Project structure
The Spectral Clock project consist of a few connected parts, because it isn't itself only a software. The project is divided into:

| **Hardware**     | **Microcontroller**     | **PCBs**           | **Mobile app** |
|-------------------------------------|-------------------------------|-----------------------------------|-----------------------------------|
| Engine, connection between parts, wood case and different harware stuff related to the device construction| STM32 project written in HAL library help and STMCubeMX generator which has the logic responsible for controlling the image displayed by leds| Clock's bar designed in Altium environment with the microcontroller, leds and rest electronic elements. Also PCB for BLDC controller | The user interface which is Android mobile application written in Java. Enables changing the images by user remotly via bluetooth |

## Questions or need help?
Don't hesitate to send me a mail on jakub.wieczorek0101@gmail.com.

## Copyright and license
Spectral Clock project is copyright to Jakub Wieczorek under the [MIT License](https://opensource.org/licenses/MIT).

[wiki]: https://github.com/jakubwieczorek/spectral_clock/wiki
