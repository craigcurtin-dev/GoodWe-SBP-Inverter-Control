# GoodWe-SBP-Inverter-Control
This repository will document all knowledge i can find on the control and reporting from GoodWe SBP5000


The SBP5000 (and presumably the SBP3600) are AC coupled retrofit inverters from GoodWe that provide great performance at a low cost.
They appear to use the same command set at the ES/EM series from GoodWe and only support Modbus ovr RS485 (RTU).
They have a dedicated port that is used for RS485 labelled as the EMS port on the unit - this has a default Modbus address of 247 (0xF7 hex) and operates at 9600/N/8/1
