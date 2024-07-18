# ANAVI Fixed Power Delivery

Small 2-layer fixed USB-C PD power sink with [CYPD3177](https://www.infineon.com/cms/en/product/universal-serial-bus/usb-c-charging-port-controllers/ez-pd-barrel-connector-replacement-bcr/cypd3177-24lqxq/) and 2 pin terminal block.

The board provides a fixed output from USB-C PD (Power Delivery) using the CYPD3177 chipset. It's highly flexible, allowing USB-C Charging up to 15W and USB-C PD up to 100W. Unlike many other chips available, it does not require any firmware nor flashing, and power settings are configured with pullup and pulldown resistors. This design is inspired by [CYPD3177-Breakout](https://github.com/Hugoyhu/CYPD3177-Breakout). Resistors R1 and R2 set the maximum current, which is 2A according to the default values in the schematics. By adjusting the values of resistors R3, R4, R8, and R9, the board can be configured to a fixed output voltage of 5V, 9V, 12V, 15V, or 20V.

# License

The project is released under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Note: This is a human-readable summary of (and not a substitute for) the [license](https://creativecommons.org/licenses/by-sa/4.0/legalcode).

You are free to:

Share — copy and redistribute the material in any medium or format Adapt — remix, transform, and build upon the material for any purpose, even commercially. The licensor cannot revoke these freedoms as long as you follow the license terms. Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original. No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits. Notices:

You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation. No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.

You will have to provide a link to the original creator of the project http://www.anavi.technology on any documentation or website.

Credit can be attributed through a link to the creator website: http://www.anavi.technology
