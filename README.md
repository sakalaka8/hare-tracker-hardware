# Hare tracker hardware

Device is LoRa tracker which incudes MCU, GPS and a few sensors for enviromental monitoring.

Main components:
-TOP:
    - Murata ABZ (MCU + LoRa)
    - Ublox MAX M8Q0 (GPS)
    - Bosch BME280 (Microclimate sensor)
- ST LIS2DH12 (Accelerometer)
- AMS TSL2591 (Light sensor)
- Power supply components

PCB specifications:
- Device dimensions: 30x30 mm
- Device weight: ~30 g
- PCB thickness: 1.6mm 
- Trace to trace and trace to polygon clearance: 0.152mm (6mil)
- RF line thickness: 1.016mm (40 mil)

Assembled view
 
<img src="https://github.com/sakalaka8/hare-tracker-hardware/blob/master/DOC/tracker_top.PNG" height="200">			<img src="https://github.com/sakalaka8/hare-tracker-hardware/blob/master/DOC/tracker_bottom.PNG" height="200">			

Main power supply is from lithium-ion battery.

To do:
For lower power consumption add MOSFET (DMG6602) between MCU pin and GPS power pin.
