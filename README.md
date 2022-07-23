# DC-Motor-Velocity-PI-Controller
Basic Proportional – Integral (PI) control to control a DC Motor with encoder by using a microcontroller(PIC16F877A).


Velocity control to a DC Motor in one direction, whose velocity would be extracted with an encoder.

The reference velocity is generated with a potentiometer.

Accordance with the reference value, DC motor is driven with a PI controller. 

The controller gains (Kp and Ki) and sampling time of the control algorithm is changed via serial communication port. 

The sampling time is arranged with the timer feature of the microcontroller. 

The controller gains can be tuned manually with a default sampling time rate.
