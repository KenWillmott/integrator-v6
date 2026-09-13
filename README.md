# integrator-v6
guitar pickup test integrator V6.x

This hardware version of the integrator replaces the much older V5.8/V5.9 integrator.
General information about the integrator project is found here, along with the older design files:

https://github.com/KenWillmott/integrator/wiki

The newer V6.0 is a smaller, more integrated version of the same circuit, with upgraded components. It is possible to order a build from the factory. The BOM is a complete build, with all components, including switches and connectors. It is a fully functional integrator, needs only to be calibrated to work. A case or enclosure is recommended, So far an aluminum and an acrylic case have been used. It is possible to special order the boards without switches and connectors by noting them DNP on a modified BOM.

Complete BOM: [BOM-V601(2025-04-11).xls](https://github.com/KenWillmott/integrator-v6/blob/main/BOM-V601(2025-04-11).xls)

The project is listed at the PCBWay site, you can place an multi-board order there by following the ordering links and specifying "PCB+Assembly".
[PCBWay order link](https://www.pcbway.com/project/shareproject/W22492BSH46_integrator_V6_Gerber_e358a0f5.html)

Note that you can produce the PCB by any method, by importing the KiCad project and exporting the necessary fabrication files.

## important:
PCBWay (and some other builders) have had problems sourcing the 3-way switch. So I provided J1 to select between 3-way (100-SP3) and 2-way
(100-SP1) switches. If you have the 6.03 PCB and the 3-way switch, you should place a solder blob on J1 to close the connection. If for any
reason you have a 2-way switch, you should leave J1 as it is (default open). That will  sacrifice the ability to make approximate inductance measurements, while preserving the no-load and loaded settings (which are the most important ones).

https://github.com/KenWillmott/integrator-v6/blob/main/board-J1-settings.png
