# dumb-embedded-game

This is just a for fun thing to have something tangible to implement while messing about with embedded rust and some analogue+digital electronics. I have a STM32 Discovery board (https://www.st.com/resource/en/user_manual/dm00063382-discovery-kit-with-stm32f303vc-mcu-stmicroelectronics.pdf) which I will use.

The basic idea (for now) is to use the built in accelerometer on the discovery board to control a simple ball rolling game written in Godot and running on a PC. Some simple sound effects will be generated using some electronic hardware (buzzers, DACs etc) controlled by the embedded side.

Some general tasks:

- [ ] Godot rolling ball prototype
- [ ] Accelerometer SPI comms
- [ ] Comms between the micro and Godot
- [ ] Simple buzzer sound effects circuit
- [ ] DAC circuit
- [ ] Analogue amplification to drive a speaker


