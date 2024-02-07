<p align="center">
  <img src="https://drive.google.com/uc?id=1syhcliU9BishY8ntnnpl2gHCz8AOahTV">
</p>



# Mr.peter
peter is  simple smart plant pot with automated plant maintence and monitoring


inspired by lua smart plant pot

The project has features like:
1.temerature,humidity,day and night detection
2.automated watering based on soil moisture
3.alaram for water refill and fertilizer dosages
4.emotions to display the situation of the plant
5.fun animations like sleep,knock wake,music,etc

this also comes with additional device called "peter's hub" which is basically a automated smart watering system that can manage multiple plants at once 
### Under development

# Mr.peter's hub
This is mr.peter on steroids,this is a  smart watering system to manage multiple plants from your phone.Its easy to setup and intutive to use.

### Let me show off my pcb skills here,confuse you with some complex looking images!:)
<p align="center">
  <img src="https://drive.google.com/uc?id=11uvL8PJuoMzkoO-Sp581wbz63R7_4DnD" >
</p>

## Using Mr.peter's HUB
<p align="center">
  <img src="https://drive.google.com/uc?id=1qmEzi4bTKZtw-2fTY8pbm100rfDxRgGp" >
</p>

## How does Mr.peter's hub work?
The idea is pretty simple,we have a microcontroller,a flow valve,a relay to control the flow valve,a temperature and humidity sensor,optional I2C port,a small oled display to show some updates of the sensor data and the device state, buzzer to alert user or remind user of some task.
We just pulg one side of the flow valve to the tap and other side to the drip system which goes to each plant

## Future plans:
- I am thinking to have a seperate watering system of each plant based on their soil moisture,the watering is controlled by indivudual flow valves which are controlled by capactive soil moisture sensors attached to each plant pot.
- Maybe removing unnessary equipment from the device such as buzzers,display,etc
- Have a battery operated device which is more portable than a wired system
- Have a flow sensor to the water source to identify issues when there is no water and intimate that to the user
- Have a more simplistic app,that look good and also works well with simplistic ui
