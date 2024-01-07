# simple_network

<h4>Step 1: Add network devices to the workspace.</h4>
<p>In this step, you will add a PC, laptop, and a cable modem to the Logical Workspace.
A cable modem is a hardware device that allows communications with an Internet Service Provider (ISP). The coaxial cable from the ISP is connected to the cable modem, and an Ethernet cable from the local network is also connected. The cable modem converts the coaxial connection to an Ethernet connection.</p>
<p>Using the Device-Type Selection Box, add the following devices to the workspace. The category and sub-category associated with the device are listed below:</p>
<ul>=   PC: End Devices > End Devices > PC</ul>
<ul>=   Laptop: End Devices > End Devices > Laptop</ul>
<ul>=   Cable Modem: Network Devices > WAN Emulation > Cable Modem</ul>

![Simple Network](https://github.com/Kolapo72/simple_network/assets/147263584/ccd173d4-5413-4bea-be50-883e2e0b0086)

<h4>Step 2: Change display names of the nework devices.</h4>
<ul>a. To change the display names of the network devices, click the device icon in the Logical Workspace.</ul>
<ul>b. Click the Config tab in the device configuration window.</ul>
<ul>c. Enter the new name of the newly added device into the Display Name field: PC, Laptop, and Cable Modem.</ul>

![Simple Network Rename](https://github.com/Kolapo72/simple_network/assets/147263584/e7a3b41a-b529-418d-b22c-c940abafecdd)

<h4>Step 3: Add the physical cabling between devices on the workspace.</h4>
Using the Device-Type Selection Box, add the physical cabling between devices on the workspace.
<ul>a. The PC will need a copper straight-through cable to connect to the wireless router. Using the Device-Type Selection Box, click Connections (lightning bolt icon). Select the copper straight-through cable in the Device-Specific Selection Box and attach it to the FastEthernet0 interface of the PC and the Ethernet 1 interface of the wireless router.</ul>
<ul>b. The wireless router will need a copper straight-through cable to connect to the cable modem. Select the copper straight-through cable in the Device-Specific Selection Box and attach it to the internet interface of the wireless router and the Port 1 interface of the cable modem.</ul>
<ul>c.  The cable modem will need a Coaxial cable to connect to the internet cloud. Select the Coaxial cable in the Device-Specific Selection Box and attach it to the Port 0 interface of the cable modem and the Coaxial 7 interface of the internet cloud.</ul>

![Simple Network Cabling](https://github.com/Kolapo72/simple_network/assets/147263584/1c07c6cc-19d7-4f11-bc05-1f9284c6131b)
