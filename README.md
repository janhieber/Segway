# Segway
Building a Segway

# About
This project is about building a complete Segway.

This means there is a lot of mechanical, electronical an informatical stuff to do.

# What to do
First we should gather as much informations as possible about how
we want to build the Segway.
This includes chosing a electric motor, thinking about gear translations and this sort of stuff.

- mechanics
  - scaffold
    - maybe aluminum profile (for first tests wood)
  - wheels
  - motor
    - stepper motor? brushless motor? dunno!
- electrics / electronics
  - control board / hardware
    - some STM32F4 Discovery board
  - battery
    - small 12V Pb battery from motorcycles...
- informatics
  - regulator
    - build with Matlab Simulink
      - C code generation for STM32 platform
  - software
    - written in C
    - sensor actuator interface for Matlab Simulink generated code
    - cyclic main loop for Matlab Simulink generated code
