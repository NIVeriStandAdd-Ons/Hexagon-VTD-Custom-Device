Vires Virtual Test Drive (VTD) Custom Device
===================

The VTD Custom Device provides a connection to the driving simulation tool chain [VTD from VIRES Simulationstechnologie GmbH](https://vires.com/vtd-vires-virtual-test-drive/). It enables users to connect objects from the VTD run-time bus (RDB) to VeriStand channels to connect to models, physical IO, automotive busses, test automation and logging.  

To run this Custom Device properly you fist need to start Vires VTD Software. To configure the available object on the RDB modify "NI VeriStand 20xx\Custom Devices\Vires VTD\Data\Runtime Data Bus.xml" using the NI-XNET Database Editor.

VTD is a complete tool-chain for driving simulation applications. VTD is a toolkit for the creation, configuration, presentation and evaluation of virtual environments in the scope of road and rail based simulations. It is used for the development of ADAS and automated driving systems as well as the core for training simulators. It covers the full range from the generation of 3d content to the simulation of complex traffic scenarios and, finally, to the simulation of either simplified or physically driven sensors. It is used in SiL, DiL, ViL and HiL applications and may also be operated as co-simulations including 3rd party or custom packages. By its open and modular design it can easily be interfaced and integrated. .

### LabVIEW Version ###

LabVIEW 2020.

### Built Availability ###

Users are allowed to build anything under Build Specifications in the source's LabVIEW project(s). For an application on a real-time PXIe controller under NI Linux RT, the required built is the CompactRIO one labelled NI Linux RT x64

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices. It is used by a few customers with no problems so far.

Simulation Control Protocol (SCP) is not implemented. Usage is control of the simulation and event-driven feedback is performed via the XML-based SCP protocol in VTD.

### Dependencies ###

- NI-XNET 20.0 or later
- NI VeriStand Development Tools
- NI VeriStand Inline-Async Custom Device template

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
