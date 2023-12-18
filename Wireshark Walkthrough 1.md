<h1>Wireshark Network Traffic Capture Lab</h1>



<h2>Overview</h2>
Wireshark, a robust network protocol analyzer, allows you to capture and analyze data flowing through your network. This lab aims to provide practical experience in capturing network traffic, exploring diverse capture settings, and managing interfaces efficiently. 
<br />


<h2>Walk-through:</h2>

<p align="center">
 Launch Wireshark Interface: <br/>
<img src="https://imgur.com/s7MlDGf.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />
 
Upon launching Wireshark, locate an array of tools in the upper left-hand corner. Directly below, identify a search bar for display filters, and adjacent to it, another bar for capture filters. Beneath the capture filter search bar, find a list of interfaces available for capturing packets.

<p align="center">
 Configure Packet Capture Settings:  <br/>
<img src="https://imgur.com/Yhcc97T.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />
 
To configure your packet capture, select the "Capture Options" or settings wheel. 
 
 <p align="center">
 Input Tab: <br/>
<img src="https://imgur.com/un6l0cG.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />
  
Upon selecting the settings wheel, three tabs labeled "Input," "Output," and "Options" will appear. Navigate to the "Manage Interfaces" tab located in the bottom right.
  
  <p align="center">
 Manage Interfaces:  <br/>
<img src="https://imgur.com/w3zDf2b.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />

In the "Manage Interfaces" tab, a list of local interfaces will be displayed. Choose the relevant interface names to focus on capturing packets efficiently. This step optimizes packet captures, reducing resource usage.

 <p align="center">
 Select the "Output" Tab:  <br/>
<img src="https://imgur.com/WnWOvz1.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />

Proceed by selecting the "Output" tab within the "Capture Options."

 <p align="center">
 Configure Storage Location:  <br/>
<img src="https://imgur.com/bFzM3hm.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />

Configure a storage location for your data. Click the "Browse" tab to select a directory for saving the pcap file. Choose the desired location to streamline data organization.

<p align="center">
 Automate New Packet Captures:  <br/>
<img src="https://imgur.com/eOQ4gZn.png" height="80%" width="80%" alt="Wireshark Network Traffic Capture Lab"/>
<br />
<br />

Configure the capture to automatically create a new packet capture after every 500 megabytes. Select "Create a new file automatically" and check the "after" box. Specify that a new packet capture should be generated after every 500 megabytes.  

<h2>Conclusion:</h2>

As you navigated through the step-by-step walkthrough, you gained practical experience in configuring packet captures, exploring various settings, and efficiently managing interfaces. The upper-left array of tools, display and capture filter bars, and the interface list beneath set the stage for a comprehensive understanding of Wireshark's interface.

The "Capture Options" settings wheel served as a gateway to configuring packet capture settings. Within the three tabs—Input, Output, and Options—you delved into the intricacies of managing interfaces, a crucial aspect for focusing on specific packets and optimizing resource usage.

The exploration continued with the "Output" tab, where you configured storage locations for captured data, ensuring organized and accessible information. The automation of new packet captures after every 500 megabytes exemplified a strategic approach to handling data and maintaining the efficiency of the capture process.

This lab not only provided a technical walkthrough but also emphasized the importance of efficient packet capture in real-world scenarios. By learning to manage interfaces and tailor captures to specific needs, you've acquired skills that are directly applicable to troubleshooting, security analysis, and network optimization.

In essence, mastering Wireshark for network traffic capture is an ongoing journey, and this lab has laid a solid foundation. The skills acquired here empower you to navigate the complexities of network analysis confidently. As you continue to explore and apply these principles, you'll find yourself well-equipped to address diverse challenges and make informed decisions in the realm of network management and security. Happy capturing!
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
