# HeartHandbag
A bag for your heart that will fit in your hand

For Receiver:

Take a PCB and connect 2 LEDs in series with the signal connected to pin 9
Repeat on other side of PCB but connect signal to pin 10
Connect IR receiver to center of PCB
Connect output to ground, input voltage to 5 volts, and signal to pin 7
Attach PCB to arduino UNO
Upload receiver arduino code
Connect positive 9 volt wire to Vin pin and output to ground
Connect wires into a cage to keep bag from collapsing
Place setup into wire cage
Close cloth around setup
Tie top with yarn

For Emitter

Take PCB and insert arduino nano
Connect IR emitter diode to pin 3 and output to ground
Connect output of pulse sensor to ground, input voltage to 5 volts, and signal to A0
Connect 9 volt output to ground, input to single pole double throw switch and then to Vin pin 
Attach elastic to PCB with hot glue and hook and eye closure
Upload arduino emitter code (use old bootloader for arduino nano)
