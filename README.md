# dumb_mtr_board
Motor controller board

DUMB_MTR Board provides a small standalone interface for driving a stepper motor.

Core functions:

* Power input from 5-24V
* Stepper motor output connector
* Forward and reverse jog buttons
* Speed adjustment potentiometer
* RGB/status LEDs
* UART header for driver configuration/debugging
* Manual local control without needing the Brain_Board

Input power:     5-24V
Motor driver:    TMC stepper driver module
Controls:        FWD / REV buttons
Adjustment:      Speed potentiometer
Indicators:      Power / direction LEDs
Motor output:    4-pin stepper connector
Logic rail:      On-board 3.3V regulator


# DUMB_MTR Board

A compact standalone stepper motor control board built around a TMC stepper driver module.

This board is designed as a simple hands-on motor controller with local direction controls, speed adjustment, motor output, status LEDs, and a selectable input power source.

## Project Status

Hardware revision:

```text
DUMB_MTR_BOARD_V1
REV A