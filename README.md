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

## Important!:
Some manufacturers and myself, have had problems sourcing the 3-way switch. So I provided onboard solder jumper J1 to select between 3-way (100-SP3) and 2-way
(100-SP1) switches. If the 100-SP3 is available, PCB V6.02 will work with no modifications and PCB 6.03 requires a solder blob on J1. If the 100-SP1 must be used, PCB V6.03 will work with no modifications and PCB V6.02 requires that C1 be either removed or not placed during production. Using the ON-ON functioning of the 100-SP1 will sacrifice the ability to make approximate inductance measurements, while preserving the no-load and loaded settings (which are the most important ones).

<img width="452" height="116" alt="board-J1-settings" src="https://github.com/user-attachments/assets/0b1c5b91-30e5-41ee-9562-d95f330f82d4" />

From a pure manufacturing point of view, the combinations

V6.02 --> 100SP3T1B4M7QE
V6.03 --> 100SP1T1B4M7QE

are preferred, since those configurations require no board or BOM modifications

