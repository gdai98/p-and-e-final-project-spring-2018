# Plant Monitoring Device

This is a device that can monitor the soil moisture and amount of light for a plant.


## Summary

For this project, Jamie Catacutan and I wanted to create a device that would help with taking care of plants. Initially we wanted to use a screen to display the different areas to be monitored (moisture, light and temperature), but we spent a lot of time and couldn't figure out how to get the screens to work. Instead, we used a Neopixel Stick to indicate soil moisture and temperature levels, and a switch to toggle between the two levels on the Stick.

We used two nails as moisture sensors and a light sensor. The two nails are to be placed into soil to measure the moisture, which will be displayed on the Neopixel Stick via blue light; the bar is completely lit if there is enough water, and depletes if there is not enough. The light sensor picks up the amount of light for the surrounding area, and is indicated on the Neopixel Stick via green to yellow light in the same manner.

## Component Parts

We used an Adafruit Feather 32u4, two breadboards, two nails, one light sensor, one switch and one Neopixel Stick.

The input data includes moisture value from the nails and light value from the light sensors, as well as the value of the switch for the Neopixel Stick.

The output data include the code and the light levels indicated on the Stick.

![Diagram](https://raw.githubusercontent.com/gdai98/p-and-e-final-project-spring-2018/master/diagram.jpg)

## Challenges

The most challenging part was trying to use a screen to display the monitored levels described above. We tried two screens - the first screen worked initially and was displaying correctly, but suddenly stopped working. Only the backlights for the second screen worked, yet there were no pixels showing up. Due to time constraints, we decided to use a Neopixel Stick instead to display the levels.

The other challenging aspect was wiring everything together - the large amount of wires together quickly became confusing, and when problems arose, we weren't sure where the issue was. Some miswiring and a lack of a resistor led to our moisture sensors to be jumping and spiking when the nails were dry; however, with some help, we were able to fix it.

## Timeline

- Week 1: Write proposal
- Week 2: Wired up and figured out the code for moisture sensors
- Week 3: Tried to connect screens
- Week 4: Used Neopixel Stick and added a light sensor and switch, figured out the code
- Week 5: Present!

## Completed Work

![Moisture](https://raw.githubusercontent.com/gdai98/p-and-e-final-project-spring-2018/master/moisturepic.jpg)
[Link to moisture video](https://github.com/gdai98/p-and-e-final-project-spring-2018/blob/master/moisturevid.mp4)
![Light](https://raw.githubusercontent.com/gdai98/p-and-e-final-project-spring-2018/master/lightpic.jpg)
[Link to light video](https://github.com/gdai98/p-and-e-final-project-spring-2018/blob/master/lightvid.mov)


## References and links

http://www.instructables.com/id/Plant-Moisture-Sensor-W-Arduino/
http://gardenbot.org/howTo/soilMoisture/
https://www.electronicsweekly.com/blogs/gadget-master/arduino/build-plant-monitor-arduino-2016-09/
http://www.deviceplus.com/how-tos/arduino-guide/an-arduino-plant-monitoring-watering-device/
http://www.instructables.com/id/Moisture-Detection-With-Two-Nails/
https://learn.adafruit.com/adafruit-neopixel-uberguide/basic-connections
https://www.adafruit.com/product/1426?gclid=EAIaIQobChMI8Mv0tYjf2gIVEcJkCh2h7QqvEAkYCCABEgJX-vD_BwE
https://learn.adafruit.com/adafruit-neopixel-uberguide/powering-neopixels
https://www.hackster.io/zanycadencedev/getting-started-with-arduino-and-neopixels-013360
https://www.hackster.io/zanycadencedev/getting-started-with-arduino-and-neopixels-013360
