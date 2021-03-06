OpenSourceLabEquipment
======================

Open Source Lab Equipment project integrates the solutions from our development projects into standalone solutions to increase the flexibility, hackability and versatility of new and existing equipment in development & research laboratories. A set of solutions is introduced for linear precision positioning, mimicking the high-grade translation stages at a fraction of cost using low-cost 3D printing. Designs vary from fully 3D printed low-performance to hybrid 3D printing using teflon sliding surfaces. The designs can easily be motorized for precision remote control or the approach implemented on existing high-grade translation equipment.

![MotorizedLinearStage](https://raw.github.com/IRNAS/OpenSourceLabEquipment/master/LinearTranslationStages.jpg)

## Linear translation design overview
Linear translation stages generally consist of three main stages, the base which can be firmly mounted, the slider for mounting the experiment object and the adjustment mechanism commonly consisting of a fine-pitch threaded screw and a counter-spring.

Published design are generally independent of the adjustment mechanism, either a fine-pitch threaded micrometer screw can be used, for smaller resolutions M3 or M4 screws work equally well.

### Linear Translation Plastic Slider
This linear translation stage features a plastic-plastic slider, making the design very 3D printable as well as low-profile. Precise tolerances are required to achieve good sliding action with great accuracy.

### Linear Translation Teflon Slider
The improved translation stage features teflon tubing as the sliding element, improving the sliding action while slightly reducing 3D printing tolerances. This approach can be easily sopted by non-uniform shapes of sliding elements for most versatile use.

#### Assembly
Print the parts individually, use 4mm reamer to cut the holes for tubing to precise dimension, use 4mm outer 2mm inner teflon tubing. Adjust the size of the slider if the sliding aciton is not smooth by scaling it.

### Motorization
The designed stages can be easily motorized by adding a stepper motor for driving the precision screw, however the same approach may apply to high-grade manual translation stages, for a various number of axis. The developed application demonstrates this approach.

---

#### License

All our projects are as usefully open-source as possible.

Hardware including documentation is licensed under [CERN OHL v.1.2. license](http://www.ohwr.org/licenses/cern-ohl/v1.2)

Firmware and software originating from the project is licensed under [GNU GENERAL PUBLIC LICENSE v3](http://www.gnu.org/licenses/gpl-3.0.en.html).

Open data generated by our projects is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

All our websites and additional documentation are licensed under [Creative Commons Attribution-ShareAlike 4 .0 Unported License] (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

What this means is that you can use hardware, firmware, software and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

Koruza, GoodEnoughCNC and IRNAS are all names and marks of Institut IRNAS Rače. 
You may use these names and terms only to attribute the appropriate entity as required by the Open Licences referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.

