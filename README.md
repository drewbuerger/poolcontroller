# Pool Controller

## Hardware

[Apex Aquarium Controller System](https://www.bulkreefsupply.com/a3-apex-controller-system-neptune-systems.html?queryID=9409e28c16d811f17f7a58c95c82f18b&objectID=14772&indexName=brs_prod_m2_default_products)
_Has built in ORP, pH, & Temperature sensors.  Also allows for programing logic to dispense chemicals send water to roof when temperature is above current water temperature._

[Apex DOS Dosing and Fluid Metering System](https://www.bulkreefsupply.com/dos-dosing-and-fluid-metering-system-neptune-systems.html?queryID=0a9b3bd4c198aa5c6f5492fc08fee6e7&objectID=4120&indexName=brs_prod_m2_default_products)
_Automaticly dispense muriatic acid & liquid chlorine_

[Apex FMK Flow Monitoring Kit](https://www.bulkreefsupply.com/fmk-flow-monitoring-kit-neptune-systems.html?queryID=aa8d143f81925cfdd40c157b5db32515&objectID=6041&indexName=brs_prod_m2_default_products)

[Apex Flow Sensor 1"](https://www.bulkreefsupply.com/1-flow-sensor-fs100-neptune-systems.html?queryID=d609a56eb41403af2a0a9bc773b45af4&objectID=6044&indexName=brs_prod_m2_default_products)
_Determine when enough water is flowing to dispense chemicals & take accurate measurements_

[Apex Flow Sensor 2"](https://www.bulkreefsupply.com/2-flow-sensor-fs200-neptune-systems.html?queryID=e13cbb9b12136bece87a24e6f4661131&objectID=6043&indexName=brs_prod_m2_default_products)
_Overall flow of water to help assure enough turns_

[Pentair 2-Way Pool Diverter Valve](https://a.co/d/0Nok9Lb)

[Pentair 3-Way Pool Diverter Valve](https://a.co/d/gXk6q7s) 

[Intermatic PE24VA Valve Actuator](https://a.co/d/9ht9lFy)
_Used to turn on/off water fall & send water to roof for solar heating_

[Transformer 110/120V to AC 12V/5A](https://a.co/d/flX0aWJ)
_Used to control Hayward pool pump.  Pump has 4 relays (true/false) which allows controller different speeds + 1 relay (on/off)._

[In-line Probe Holder](https://www.bulkreefsupply.com/probe-holder.html)
_3 to hold pH, Temp, & ORP sensors_

[SCH 40 2" 2" 1/2"](https://a.co/d/533dbGo)
_Used to screw in 3 probe holders_

[Clear SCH 40 PVC](https://a.co/d/1xcCEcu)
_Allows user to assure water level in DOS & Sensor areas_

Misc SCH 40 PVC Pipes & Fittings

[Pump]()

[DE Filter]()

[Solar Panel on Roof](https://umasolar.com/solar-pool-heater/)

[Tractor Supply 25 gal Storage](https://www.tractorsupply.com/tsc/product/buyers-products-26-gallon-domed-storage-tank)
_Storage tanks for muriatic acid(4:1) & liquid chlorine(1:1)_

[Float valve 1/2" MNPT](https://a.co/d/8fwWH7V)
_Simple dump float valve to automaticlly add water when low below certian level._


## Software
[Apex](https://www.reef2reef.com/threads/apex-programming-command-reference.755622/)

[Home Assistant](https://www.home-assistant.io/)
_Used as only a Dashboard & Apple watch interface.  No logic is used in Home Assistant._
![Screenshot 2024-05-20 at 1 57 36 PM](https://github.com/drewbuerger/poolcontroller/assets/77402847/347d6c11-f8ef-4b85-9748-3a8f2756f847)


## Setup 
_2" SCH 40 unless noted_

Water flows in from 4 skimmers (Pool), return from probes, & 2 buttom drains (Spa & Pool)

3-way valve allow control of water coming from pool/probes, spa, or all.

Then into Pool Pump followed by Multiport, DE Filter.

Then splits 1" to probes & DOS(Chemical Dispenser), 1" pipe splits again to probes which expains to 2" pipe to lower pressure and up to chemical dispenser which then pipes directly into center of pool on a spinning jet return. 

2" continues to 3-way valve with Actuator sending water either to roof for solar heating or bypassing solar

Another 3-way valve with Actuator is hit to determine water running to pool vs hot tub/waterfall
<img width="923" alt="Screenshot 2024-05-20 at 2 53 11 PM" src="https://github.com/drewbuerger/poolcontroller/assets/77402847/ec53ed0d-f859-43b3-9ffa-9911c9c63ba6">


