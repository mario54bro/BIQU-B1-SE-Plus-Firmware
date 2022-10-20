# BIQU-B1-SE-Plus-Firmware
Working on B1 SE Plus Firmware for Stepper Drivers TMC2226 (or TMC2209), Fan Controller only controls one connector currently, so you will want a Y adapter to power both case fans.
Fan controler will only power the fan case fan port when the stepper motors are active, and will power off the case fan port after 60 seconds after the motors are turned off.'
This will also remove the original BTT interface and just use the marlin interface.
