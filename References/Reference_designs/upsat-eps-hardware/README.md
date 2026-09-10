# upsat-eps-hardware
EPS Hardware for UPSat

A pcb module implementing the Electric Power System of UPsat Cubesat. 
The EPS ssubsystem is responible for:
 - Charging the three cell baterry bank from five availiable solar cells implemeting MPPT algorithm for maximum availiable power harvest.
 - Providing stable 5V and 3.3V power rails.
 - Protecting the battery pack from low temperatures.
 - Deploying the COMS subsystem Antenas.
 - Respoding to OBC UART messages for battery/energy status and voltage rails control.
 
 There is an existing design, EPS version1, wich will be used as a test framework, to deliver eps version 2 board.  
