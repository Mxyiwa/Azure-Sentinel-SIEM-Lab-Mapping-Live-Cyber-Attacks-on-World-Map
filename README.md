<h1>Azure Sentinel SIEM Lab to Map Live Cyber Attacks</h1>

<h2>Description</h2>
<b>
 This lab was designed to create a virtual machine to map out live cyber attacks on a world map using a vulnerable Azure Virtual VM (Honeypot) on the internet and then monitor and log attacks from different IP addresses from different countries all over the world and display the data on a world map to visualise where all the attacks are coming from.
</b>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<h2>Link to hands on step-by-step guide on how to perform this project</h2>

- <b>https://medium.com/@fadareoluwamuyiwa/azure-sentinel-siem-lab-to-map-live-cyber-attacks-d74c2426d59b</b>

<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API
- <b>Parallels VM</b>

<h2>Environment Used</h2>

- <b>Windows 11</b>

<h2>Attacks from Luxembourg, Germany and, Belgium coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://imgpile.com/images/hoXc8X.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 5 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://imgpile.com/images/hoXba3.png" height="100%" width="100%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
