# plantWatcher
An esp8266 circuit and sketch to monitor conditions for seed starting and plant growing. Currently no control functions. 

## Future State
* Watch multiple soil moisture sensors and DS18b20 temperature probes, indexed to location. 
   - Currently 6 ea due to limit of 4051 chip with LDR and battery (coming later).
* Watch DHT11 for local environmental conditions
* Watch LDR to verify light on/off
* Easy-ish plug-in programming of sensors. 
   - Combine moisture and temp probes in a single package
* _Coming Later: Operate from battery_
* Display data in Blynk 
   
## Key Technologies
* Read and display 4051 chip channels
* Recognize added probe
   - Tie new probe to 4051 chip channel
   - Recognize new DS18b20 address on 1-wire(tm) bus.
* Read DHT
* _Coming Later: Battery technologies_
   - _Choose Battery option: Protected or pre-made pack_
   - _Make ESP deep sleep work_
   - _Optimize for speed and power usage_

## Journal
