# Software_Engineering 

FOR MORE DETAILS -> POWER POINT PRESENTATION.

DESCRIPTION:
The project concerns a single appliance that includes 4 different devices:
1. Washing of laundry
2. Laundry drying
3. Dehumidification of room area (outside the appliance)
4. Room air heating (outside the appliance)

All functions must be managed by a single software capable of:
- Enable individual management of each function
- Allow automatic management that will control multiple activated functions (two, three or all four)
- Automatic management must manage the simultaneous operation of several functions harmonise them in order to avoid exceeding a certain absorption threshold of electricity set by the user, such as 2300 watthours, which would cause the deactivation of the energy by the limiter.
- Allow the end-of-wash and end-of-dry dates of two different loads of laundry, put one to wash and the other to dry simultaneously. 
- Manage contemporary washing and drying activities according to required dates by the user, with the lowest energy consumption.
- Assess whether the dates requested by the user are feasible, if not, not accept but propose the date or dates closest to those requested.
- Indicate for each chosen solution the total expected energy consumption. In order to perform the necessary calculations, the software must have access to a certain amount of data,some inserted by the customer during the installation of the appliance:

Geographical and altitude data:
- Region (e.g. Lombardy)
- Altitude (e.g. mountain, hill, sea)

Environmental data:
- Dimensions of the room in which the appliance is placed (cm. 300 x 200 x 270), used for 
calculate the amount of air available.
- Presence of openings in the room : number of doors, number of windows.
- Indication of where these openings enter (inside or outside the house).
- Whether and which of these openings are to be considered closed and which are to be open (this may be modified according to the season)

Time data:
- Time of day/day of month/month of year/year

Other data the software must be able to obtain them through special sensors:
- Ambient air temperature
- Relative humidity ambient air
- Type and weight of laundry, drying and washing.
For example, I have just washed a load of 5 kilograms of cotton, centrifuged at 1,000 turns, and I put it to dry, at the same time I put to wash a second load of 4 kilograms of mixed fabrics, with centrifuge at 800 turns. The type of laundry is assumed by the programs 
selected, the weight of the laundry by sensors can detect it (some washing machines already have these sensors). The humidity of the laundry to dry is assumed according to the type of fabric and the centrifuge turns.
The software, according to the user’s requests, if acceptable, chooses the solutions suitable for 
meet the set dates of end washing and end drying with the least consumption of energy.
The software must be able to check the results obtained and compare them with those required for adapt and repair, if necessary, their calculations.
For this purpose must also be able to detect atypical situations (for example if the appliance is placed in the bathroom, the 
appreciable increase in relative air humidity when the user takes a shower).
In case such atypical situations become habitual (eg: the user has the habit of showering all evenings around 20:00) consider them in their own elaborations.

DOCS:

[Modello di analisi - RAD](https://github.com/MattiaDiPalma00/Software_Engineering/blob/main/Progetto%20ing%20software/Modello%20di%20analisi%20-%20RAD.pdf)
[Modello di progettazione - SDD](https://github.com/MattiaDiPalma00/Software_Engineering/blob/main/Progetto%20ing%20software/Modello%20di%20progettazione%20-%20SDD.pdf)
