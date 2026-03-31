# WingFCplot
wing flight controller database

Place Holder manual:

I am loosely defining a wingFC as a flight controller with a on-board PowerDistributionBoard and a 2.54mm pitch servo rail.

Manufacturer ●trading name of the product.
Model        ●item in the product line.
Dimension    ●outside measurements of the FC.
Mount        ●size of the holes between the sandwiched boards.
Weight       ●net weight packaging.
Input V      ●how much voltage the FC can handle.
CurrentSensor●shunt resistor scaling values.
BEC FC       ●BatteryEliminatorCircuit powering the FC.
BEC VTX      ●~9v regulator for power hungry video transmitters.
BEC SERVO    ●switchable regulator for servos
MCU          ●on-board processor
IMU          ●gyroscope/inertia measuring unit
Baro         ●Barometer/Altimeter
Blackbox     ●in-flight data logging
PWM Out      ●amount of servo rails available
UARTs        ●amount of UniversalAsynchronousReceivingTransmitting ports
I2C          ●Inter-Intergrated Circuit for peripherals
CAN bus      ●DroneCAN channel
Misc         ●notes
Cost         ●ManufacturerSuggestedRetailPrice
Betaflight   ●target support Red=false Green=true Yellow=under developement
INAV         ●target support Red=false Green=true Yellow=under developement
Ardupilot    ●target support Red=false Green=true Yellow=under developement
PX4          ●target support Red=false Green=true Yellow=under developement
