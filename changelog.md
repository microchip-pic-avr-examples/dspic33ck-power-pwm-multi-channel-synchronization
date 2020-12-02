# dspic33ck-power-pwm-multichannel-synchronization, release v1.0.0

### Release Highlights
This is the initial release demonstrating the basic configuration of a high-resolution PWM generator of the dsPIC33C family of devices. This example is part of a series of code examples highlighting specific operating modes and features.

### Features Added\Updated
In this initial version the on-board LED of the dsPIC33CK Digital Power Plug-In Module is toggled with a interval period of 300 ms, when the controller is running at maximum speed of 100 MIPS. After startup, PWM generators #1, #2 and #3 are generating three pairs of 200 kHz with 30% duty cycle complementary PWM waveforms at the PWM1H/PWM1L, PWM2H/PWM2L outputs and PWM3H/PWM3L respectively. These three complementary pairs of PWM waveforms are in phase to each other. By pressing the on-board push button USER on the Digital Power Development Board, the three in-phase complementary PWM pairs is changed to a three-phase PWM system with a phase angle separation of 120 degrees, that is PWM2H/PWM2L pair is advanced by 120 degrees from PWM1H/PWM1L and PWM3H/PWM3L is advanced by 120 degrees from PWM2H/PWM2L. The system is toggled for in-phase PWMs to mulit-phase PWMs with the USER switch.



