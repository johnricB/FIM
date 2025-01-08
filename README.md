<h1>Hashing Algorithms + Coding up a File Integrity Monitor (FIM)</h1>



<h2>Description</h2>
The system continuously monitors for any changes to the files and configurations..
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows PowerShell ISE</b>
  


<h2>Scope</h2>


- <b>Improved Security Posture</b>
   - <b>Helps maintain the integrity of critical systems and data.</b>
- <b>Alerting and Response:</b>
   - <b>If any unauthorized changes are detected (e.g., file modifications, deletions, additions), the FIM system generates alerts.</b>


<h2>Environments Used </h2>

- <b>Windows 10</b>


<h2>Program walk-through:</h2>

<p align="center">
Ask the user what they want to do. <br/>
<img src="https://i.imgur.com/P1rxLPT.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Collect new Baseline.<br/>
<img src="https://i.imgur.com/gPyH1a9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zzIcKdp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Begin monitoring files with saved Baseline<br/>
<img src="https://i.imgur.com/MGywKvX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/T8pkKJv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Notify the user if a file is changed or deleted.<br/>
<img src="https://i.imgur.com/ASjH8C1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ea1rxw2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
