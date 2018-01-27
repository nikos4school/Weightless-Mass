# Weightless-Mass
Astro Pi 2016-2017 contest contribution of Intercultural Jr High School of Evosmos

Our team had to complete 2 missions.

The first mission was set by the organizers while the second one was proposed by the Weightless Mass team.
The first mission was to detect the presence of a crew member in the Columbus module. For this mission we used the measurements of the relative humidity. An increase in this quantity is an indication that someone was entered in the module, while a decrease is an indication that someone was left the module.

Our proposal had two parts:
1. To detect when the ISS has limited protection by the earth's magnetic field and to issue a warning message in a such situation.
2. To calculate the period of the orbit of the ISS.

To accomplish those two missions we had to measure and log the strength of the magnetic field every 10 s. For both parts we used the 3 components (X, Y and Z) and calculated the composite strength.

If the strength is less than a minimum limit, then a warning message as red color is issued on the display of the Astro Pi. When the field is higher than the above limit, then the display is turning green.

For the second part of the mission we calculated the time between changes in the magnetic field.
