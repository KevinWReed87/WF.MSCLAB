<img src="https://i.imgur.com/BkbsIKk.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h1>Securing Windows with Defender: GitHub Lab on Antivirus and Firewall Configuration</h1>

In this lab, you’ll access and review Windows Security Virus & threat protection. Windows Defender Virus & threat protection is a built-in security feature that scans for threats on your system.

<h2>Windows Security Virus & Threat Protection</h2>

- Click the Windows Start button and select Settings.
- On the Windows Settings page, select Update & Security.
- Under Update & Security, select Windows Security.
- Select Virus and threat protection.

<img src="https://i.imgur.com/LVVbOE9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/PwzJIWC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/MzoGjAk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/Kux5gwh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/MarjUgB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

This screen shows the following features:

<img src="https://i.imgur.com/zeicrIS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/Gc0SYLt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>


- Current threats: Here, you can see any threats that have been detected on your device. You can see when the last scan occurred, how long the scan took, and how many files were scanned. Here you can also click the button to start a quick scan or access scan options to run a full scan or a custom scan.

- Virus & threat protection settings: Here, you can access options for managing your virus and threat protection settings. You can customize your protection level, opt to send sample files to Microsoft, exclude files or folders from scans, or temporarily stop your protection.

- Virus & threat protection updates: Here, you can view the last time your virus definitions were updated. You can also opt to manually check for updates.

- Ransomware protection: Here, you can choose to enable controlled folder access. This protects memory, files, and folders from unauthorized changes.

<h2>Update Threat Definitions</h2>

Windows Security uses security intelligence, also known as definitions, to identify known threats. These definitions include information about known threats. These definitions are updated automatically, but if you suspect a problem with your system, you should ensure that threat definitions are up-to-date before you run a scan.

- Under Virus & threat protection updates, select Check for updates.

<img src="https://i.imgur.com/8eUTV9N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click check for updates

<img src="https://i.imgur.com/AROONpw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/a1JKW4k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Run Antivirus Quick Scan</h2>

Now we can run an antivirus scan. Click the Quick scan button on the Virus & threat protection screen. The scan will take several minutes to run. When complete, the Quick scan button will reappear. 

<img src="https://i.imgur.com/37Ja9fB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Threat history to view any recent findings.

This page shows you the results of the last scan. You see the files identified as a threat and quarantined, so they cannot damage your device. You then see files identified as potential threats but allowed to continue running.

<img src="https://i.imgur.com/W5gUETV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Run A Custom Scan</h2>

- I will run a custom scan that only scans the files in the Downloads folder.

<img src="https://i.imgur.com/QUMjTVG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<img src="https://i.imgur.com/rMKIjzX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

No files are present in the Downloads folder for this lab, the scan will not find anything to scan. In a custom scan, you can usually select specific files or folders to include in the scan. This is just a example of how it would be conducted.

<h2>Configure Firewall Rules Using Windows Defender Firewall</h2>

In this lab I will review Windows Defender Firewall configuration.

- Click the Windows Start button. and then select Windows Security.

<img src="https://i.imgur.com/7mBscU5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Firewall & network protection.

<img src="https://i.imgur.com/9kXjRiO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Here you will see the firewall status for the following:

- Domain network
- Private network
- Public network

<img src="https://i.imgur.com/Rzzgwd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Domain network.

<img src="https://i.imgur.com/Bo4Jf4d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>


Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming domain network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

<img src="https://i.imgur.com/Z1l2jhT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Private network.

<img src="https://i.imgur.com/e2dJiSE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming private network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

<img src="https://i.imgur.com/H1KaWwk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Public network.

<img src="https://i.imgur.com/VUkhKIC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Verify that the Windows Defender Firewall is toggled to On. Note the checkbox under Incoming connections. This is a quick access location that blocks all incoming public network traffic – even traffic that is normally permitted. Select the back arrow button to return to the Firewall and network protection window.

<img src="https://i.imgur.com/W3srNZ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Click Allow an app through firewall.

<img src="https://i.imgur.com/AfBhU7d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Scroll to Mozilla Firefox. Note that the current configuration allows for Firefox to communicate on the Private network but denies it from communicating on the Public network.
- Click the Public box next to Firefox. A checkmark will appear. Click OK to return to the Firewall & network protection screen. Users will now be able to use Mozilla Firefox on the public network.

<img src="https://i.imgur.com/95tYwyc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Configure Firewall Rules using Windows Defender Firewall with Advanced Security</h2>

For this lab, we want to use Windows Defender Firewall with Advanced Security to edit an existing firewall rule. We want to enforce the following rules:

Allow the connection for Key Management Service on the Domain and Private network.

Deny the connection for Key Management Service on the Public network.

- Select Advanced settings on the Firewall & network protection screen.

<img src="https://i.imgur.com/ip7ejR7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

 Here you will see an Overview in the center panel. There are two rule types listed on the left panel:

- Inbound Rules

- Outbound Rules

Each of these rules can be configured to filter traffic based on computers, users, applications, ports and protocols

- Click Inbound rules.

<img src="https://i.imgur.com/a7cJWim.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Within this list of inbound rules, the presence of a green checkmark beside some rules signifies that those rules are currently active, permitting inbound communication. On the other hand, rules lacking a checkmark are present and ready for use but are not currently enabled.

<img src="https://i.imgur.com/9qtj9i9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

To locate the Key Management Service inbound rule in the Overview panel of Windows Defender Firewall with Advanced Security, please scroll down. Take note of the following details: The rule is presently not enabled, as indicated by the 'Enabled' column showing 'No.' If you were to enable this rule, it would allow communication, as the 'Action' column states 'Allow.' To access and modify this rule. 

- Simply double-click on it.

<img src="https://i.imgur.com/tzkEZSF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Within these rule details, on the General tab, you'll find important information about the rule. This includes the rule's name, a description explaining its purpose, and whether the rule permits or blocks connections. In this specific instance, the rule allows the connection.

- Click the Advanced tab.

<img src="https://i.imgur.com/4d6wfPj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

All the profile rules are selected but we only want the domain and private rules selected.

-Uncheck public, then click apply, then click ok

<img src="https://i.imgur.com/ExxvH23.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/tE56izz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

Now we will create an inbound rule that blocks communication with the public network. Since the new rule will be similar to the last, we will copy the existing rule. Right-click the Key Management Service (TCP-In) inbound rule and click Copy. Press Ctrl+V to paste.

<img src="https://i.imgur.com/Gcbwc3T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

You will now see a second Key Management Service (TCP-In) inbound rule. Double-click the second rule to open the **Key Management Service *TCP-IN) Properties.

<img src="https://i.imgur.com/kS5XWHs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

We want to block connection with the public network, select Block the connection on the General tab. 

- Click Apply.

<img src="https://i.imgur.com/tn31gCc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>


- Click the Advanced tab.
- Remove checks from domain and private boxes.
- Click public to add check
- Click Ok

<img src="https://i.imgur.com/NVQ66fn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Right-click each Key Management Service (TCP-In) rule and click Enable rule.
- Now, take a look at the first rule, and you'll notice a green checkmark next to it, indicating that this rule, which allows communication, is currently enabled. The second rule is marked with a circle and a line through it, indicating that this rule, responsible for blocking communication, is also enabled.

<img src="https://i.imgur.com/1Kozvsz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>





<img src="https://i.imgur.com/5fHW5CN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>









