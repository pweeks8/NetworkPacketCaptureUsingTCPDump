<h1>Network Packet Capture using TCPDump</h1>

<h2>Description</h2>
Lab consists of using TCPDump to capture network packets.
<br />

<h2>Applications Used </h2>

- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>In browser virtual machine</b>

<h2>Lab walk-through:</h2>

<p align="center">
Identified network interfaces: <br/>
<img src="https://i.imgur.com/peBEPJZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Used tcpdump to identify interface options available for packet capture: <br/>
<img src="https://i.imgur.com/Yx6LkgS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Network traffic on eth0: <br/>
<img src="https://i.imgur.com/umOZP6H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Network traffic captured using tcpdump: <br/>
<img src="https://i.imgur.com/NzuNoLO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Filtered the captured packet data: <br/>
<img src="https://i.imgur.com/FEyZMjm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/WyWZ9CB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/uQtwOh3.png height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />

<h2>Summary</h2>

- In this lab, I practiced using tcpdump to capture network data for inspection, interpreted the information that tcpdump output for the captured packet, and save and loaded the packet data for later analysis. 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
