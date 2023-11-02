# NTI_AVT_Smart_Home
NTI FINAL PROJECT " Smart Home System "
I'd like to share our final project at National Telecommunication Institute (NTI) in the Embedded Systems track, Level 2, focusing on AVR interfacing. My project is a SMART HOME SYSTEM, and it's a culmination of a month's hard work.

**Project Components:**
- **Drivers:**
 - HAL LAYER :
  - LCD
  - KPD
  - DC_MOTOR
  - LEDs
  - SERVO_MOTOR
 - MCAL LAYER :
  - DIO
  - EXTI
  - ADC
  -TIMER1

We've implemented some exciting features:
- We have a smart door locker that accepts a password via a keypad. If the wrong password were entered three times, it activates a halt system and triggers a BUZZER. On successful entry, the door is opened by a servo motor, and the system status is displayed on a 4x20 LCD.

- Our system uses a LM35 temperature sensor and an LDR sensor. The air conditioner is connected to a DC motor, and the temperature sensor controls it. If the temperature exceeds 28°C, the DC motor opens it, and if it drops below 21°C, it closes it. The LDR sensor controls the room lighting. If light levels drop below 50, it activates the LEDs.

- Additionally, we've incorporated dimmable LED lights, adjustable via a potentiometer.
