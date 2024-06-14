<h1>Active Directory within Oracle VirtualBox</h1>




<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will create two Virtual Machines on Oracle VM, one as a Domain controller running on Windows Server 19, and other as a client PC running Windows 10.
<br />
<br />

<p align="center">
<img src="https://imgur.com/nV1w8oo.png" height="60%" width="60%" alt="ActiveDirectoryMap"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Automate creating users on Active Directory
<p align="center">
<img src="https://imgur.com/a/s4320sX.png" height="85%" width="85%" alt="Namecreator Powershell"/>
</p>

<h2>Attacks from various locations coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://imgur.com/kEJCJIL.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 2 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://imgur.com/dnYYySq.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
