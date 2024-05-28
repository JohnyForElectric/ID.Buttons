# ID.Butnz a.k.a ID.Buttons
Conventional "real" button controls for VW's MEB (electric) platform

# Euro style taillights "ID.Light"
<div align="center">
  <img src="https://user-images.githubusercontent.com/107234448/183325196-1d971dd4-d042-40c1-9f65-0b1fc437ba41.jpeg" alt="(Euro-styke taillights)" width="300px">
</div>

## What
We are excited to announce developement of ID.Butnz a.k.a. ID.Buttons that will bring back the option of physical button controls for select functions in VW's MEB platform. Initially designed for VW ID.4 electric vehicle, it will make it simpler to control specifc car functions with physical buttons. Button functions can be either assigned to a specific car functions (like heated seat) or to set of functions - we call them macros - like seat heater 1, steering wheel heating 2.    

## Why
While some manufacturers and brands are moving away from dedicated buttons for the driver, VW is going the .

## When
There are two types of taillights available for the ID.4. The "base" style (option 8VG) and the smart "ID.Light" (option 8VP). The latter only available in Europe in higher trim vehicles. The US taillights used for model years 2021 and 2022 are simple modification of the "base" Euro. The yellow turn light LEDs in the unit are replaced for red. In addition the US spec taillight has an internal connection between the brake segment and turn segment. As such both of these segments come on during braking and when turn light is on. The coding of the CECM (J519) "Vehicle Electrical System Control Module" is adjusted accordingly in US vehicles to "Bremslicht_ist_auch_Blinklicht"=Yes (Brake light is also turn light). In addition, the taillight connector has one less pin and the wire harness one less wire. This makes it harder to retrofit yellow rear turn lights into US vehicles.

## What's next
There are two types of taillights available for the ID.4. The "base" style (option 8VG) and the smart "ID.Light" (option 8VP). The latter only available in Europe in higher trim vehicles. The US taillights used for model years 2021 and 2022 are simple modification of the "base" Euro. The yellow turn light LEDs in the unit are replaced for red. In addition the US spec taillight has an internal connection between the brake segment and turn segment. As such both of these segments come on during braking and when turn light is on. The coding of the CECM (J519) "Vehicle Electrical System Control Module" is adjusted accordingly in US vehicles to "Bremslicht_ist_auch_Blinklicht"=Yes (Brake light is also turn light). In addition, the taillight connector has one less pin and the wire harness one less wire. This makes it harder to retrofit yellow rear turn lights into US vehicles.

---
**NOTE**

The retrofit of EURO ID.Light into US vehicle as described below is validated as working in **ID.Software 3.1.0**.
(For ID.Software 3.1.0 the adaptation "Bremslicht_ist_auch_Blinklicht" was removed along with other six adaptations in the "Fahrlicht_Bremslicht_Standlicht_SAM" category from J519/CECM.)

**The OTA update 3.2.11** (aka VW action Code OUF7) installed correctly with this mod and no action was necessary after installation. No adaptations have changed.

---

The US model year 2023 physically removed the turn light segment from the taillight for better esthetical appearance as the brake and turn segments were separated by tail/parking segment.

The top spec "ID.Light" provides dynamic yellow turn signals and "welcome" animation via main 9 taillight segments. ID Furkan did a good video about those animations [here](https://www.youtube.com/watch?v=KCvncdPqyN0).

This article describes one of the possible approaches to retrofit the Euro-style premium taillight (ID.Light further) into US spec ID.4. While the process for retrofitting to Euro cars can be similar, the existing harness and coding will be different.


