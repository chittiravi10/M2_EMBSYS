# Requirments
>high level requirment (HL1)
> - - use rain sensor to detect the rain | detect the rain and send signal 
> - - LL1 -the sensor should be always working when it is on and send signal to the microcontroller
  
>HL 2
> -  turn the servo motor when the rain is detected and clean the winsheild
> - - LL2.1 Turn the acutator in such a angle that it dont break the winsheild and other components
> - - LL2.2 turn the motor repetedly untill the signal is recived 
# components 
> ## sensors
>> - ## rain sensor
>> - this sensor can detect the rain. when rain falls on the sensor(ie water) the sensor the resistance will increase and it will send signal as high. after a moment the water will conduct the electricty and the sensor will send the signal low.
> ## acutators
>> - ## servo motor
>> - the only acutator we are using is the servo motor .A servomotor (or servo motor) is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback. we can alter the speed and angle using the code given to the controller
> ## controllers
>>  ## micro controller 
>> - A microcontroller is a compact integrated circuit designed to govern a specific operation in an embedded system. A typical microcontroller includes a processor, memory and input/output (I/O) peripherals on a single chip.
>> - ## arduino uno 
>> - Arduino UNO is a low-cost, flexible, and easy-to-use programmable open-source microcontroller board that can be integrated into a variety of electronic projects. This board can be interfaced with other Arduino boards, Arduino shields, Raspberry Pi boards and can control relays, LEDs, servos, and motors as an output.
here we are going to use this micro controller to control the circuit
>> ### " here the usage of arduino is not confirm because i am researching on atmega 328 so that i can use the at mega 328 in my circuit and able to program it "