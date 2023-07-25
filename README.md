# Metro-PT3-Air_Compressor-EDA

## It describe the in depth EDA of very famous Metro Train Dataset . 

![image](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/42d720e6-3b0e-4832-9613-bcae86c5a360)

## It describe Air Pressure in the Metro Engine EDA of very famous Metro Train dataset

## Metro Train dataset describe the Air Pressure status of individual compressor in Engine.

## EDA is performed by using following Python Libraries

Numpy

Pandas

Matplotlib

Seaborn


## Following are the snapshots of different charts generated in this EDA process :

### Oil Level vs Oil Temperature

![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/48354c1b-38fa-4786-a799-79e01e2b11cd)


### Visualization of the original Time Series - 01

![image](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/f9a0145e-7b6e-4dcf-a955-2ffd701dfddb)


### Visualization of the original Time Series - 02


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/192a6029-9e9b-4ba8-bb6e-eaaa100ae04f)

### Relationship between different variables of dataset

![62e3f4bf-897b-4550-9da7-619a229dca54](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/2ed72269-11dd-4277-be5b-7d05ecb34042)


### TP3 vs H1


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/edf71160-e5dc-4f83-8387-2ec1fe075662)


### Sin Wave Plot


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/36b82fa3-5f5e-41fe-a4c9-290795317a7b)


### Histogram Plot: TP2


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/cb7eacf2-32be-45a0-ad71-101e99206dd2)


### Box Plot: TP2, TP3, H1


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/ff00fecf-f3e4-4389-8471-6e7fe6336e85)


### Pie Chart: COMP


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/dd7d037b-707c-44a5-a23a-cf16d4cbe483)


### Dist Plot: DV Pressure


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/7a7f8b6d-aae6-480b-982a-3cce76339dcf)


### Dist Plot: TP2


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/b7c51f66-7e9c-4d08-8a16-995db425bb70)


### Count Plot: Pressure Switch


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/32be4920-22fc-43b5-b22a-e2e31eca3c8a)


### Count Plot: Oil_level


![download](https://github.com/Kartik-Doye/Metro-PT3-Air_Compressor-EDA/assets/140334885/b6b98bd0-220e-4a42-bd10-8a9cb2fe3453)


# Attribute Information:

## The dataset consists of 15169480 data points collected at 1Hz from February to August 2020 and is described by 15
features from 7 analogue (1-7) and 8 digital (8-15) sensors:

- TP2 (bar) – the measure of the pressure on the compressor.

- TP3 (bar) – the measure of the pressure generated at the pneumatic panel.

- H1 (bar) – the measure of the pressure generated due to pressure drop when the discharge of the cyclonic
separator filter occurs.

- DV pressure (bar) – the measure of the pressure drop generated when the towers discharge air dryers; a zero
reading indicates that the compressor is operating under load.

- Reservoirs (bar) – the measure of the downstream pressure of the reservoirs, which should be close to the
pneumatic panel pressure (TP3).

- Motor Current (A) – the measure of the current of one phase of the three-phase motor; it presents values close to
0A - when it turns off, 4A - when working offloaded, 7A - when working under load, and 9A - when it starts
working.

- Oil Temperature (ºC) – the measure of the oil temperature on the compressor.
COMP - the electrical signal of the air intake valve on the compressor; it is active when there is no air intake,
indicating that the compressor is either turned off or operating in an offloaded state.

- DV electric – the electrical signal that controls the compressor outlet valve; it is active when the compressor is
functioning under load and inactive when the compressor is either off or operating in an offloaded state.

- TOWERS – the electrical signal that defines the tower responsible for drying the air and the tower responsible
for draining the humidity removed from the air; when not active, it indicates that tower one is functioning; when
active, it indicates that tower two is in operation.

- MPG – the electrical signal responsible for starting the compressor under load by activating the intake valve
when the pressure in the air production unit (APU) falls below 8.2 bar; it activates the COMP sensor, which assumes
the same behaviour as the MPG sensor.

- LPS – the electrical signal that detects and activates when the pressure drops below 7 bars.

- Pressure Switch - the electrical signal that detects the discharge in the air-drying towers.

- Oil Level – the electrical signal that detects the oil level on the compressor; it is active when the oil is below the
expected values.

- Caudal Impulse – the electrical signal that counts the pulse outputs generated by the absolute amount of air
flowing from the APU to the reservoirs.


