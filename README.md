## Objective
To gain practical, hands-on experience in using Lima Charlie, a cloud-based security platform, to manage security operations, improve incident response capabilities, and enhance organizational security posture in real-time.

### Skills Learned
- Telemetry Management and Data Analysis
  - Collecting, ingesting, and analyzing telemetry data from multiple sources.
  - Centralizing data to correlate security events across a wide range of assets.
  - Leveraging real-time feeds and timelines for proactive monitoring and decision-making.
- Incident Response
  - Deploying sleeper agents for rapid telemetry collection.
  - Responding to security incidents with minimal setup, ensuring quick deployment.
  - Isolating and quarantining compromised systems to prevent further breaches.  
- Security Tool Integration
  - Integrating Lima Charlie with third-party tools (e.g., VirusTotal) for enhanced functionality.   
- Real-Time Security Operations
  - Monitoring security incidents in real-time for faster response and mitigation.
  - Using Lima Charlie’s interface to manage incidents, track events, and execute containment procedures quickly.

### Tools Used
- Lima Charlie Platform: A cloud-based EDR platform for real-time endpoint monitoring, threat detection, and response.
- Kali Linux: Act as the Threat Actor's Command and Control Server.
- Windows 10 Eval: End-user machine.

## Practical Exercises

- Powershell Detection
<p align="center">
<img src="https://imgur.com/BFkztXM.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Execution of PowerShell script in the victim's machine.</b>
<br/>

<p align="center">
<img src="https://imgur.com/r3VeAnK.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Connected to Attacker's Command and Control Server.</b>
<br/>

<p align="center">
<img src="https://imgur.com/ldWttCu.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Detected the malicious PowerShell activity.</b>
<br/>

<p align="center">
<img src="https://imgur.com/ljP2IJE.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Malicious PowerShell process viewed.</b>
<br/>

- Malware Detection
<p align="center">
<img src="https://imgur.com/Y96Y8lO.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Execution of malicious file in the victim's machine.</b>
<br/>

<p align="center">
<img src="https://imgur.com/qvTCG03.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Connected to Attacker's Command and Control Server.</b>
<br/>

<p align="center">
<img src="https://imgur.com/bvGe75e.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Detected the malicious activity.</b>
<br/>

<p align="center">
<img src="https://imgur.com/hs6mrKm.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Malicious .exe file process viewed.</b>
<br/>

- Adversarial Emulation with AtomicRedTeam
<p align="center">
<img src="https://imgur.com/jscSVdh.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/wSGLFpd.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/deewLOZ.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Selected the Command and Control. Detected the malicious activities.</b>
<br/>

- Infected Machine Isolation
<p align="center">
<img src="https://imgur.com/xVUzax6.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/uA2GjNL.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/Hpwh9Yw.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Isolate the victim's machine to the network to avoid further damage.</b>
<br/>

<p align="center">
<img src="https://imgur.com/kk8mCIL.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/Os1xDfz.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/F7qw65j.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<br/>
<b>Putting back the machine to the network.</b>
<br/>

## Outcome
- Enhanced Incident Response
   - Proficiency in deploying and managing sleeper agents for quick, effective responses during security incidents.
   - Ability to quickly isolate and quarantine compromised systems to contain potential threats.  
- Improved Security Posture
   - Developed a keen understanding of customizing detection rules based on the unique threat landscape of an organization.
   - Ability to centralize and analyze data across multiple sources for better event correlation and faster threat mitigation.    
- Hands-On Security Integration
   - Acquired skills in integrating Lima Charlie with other cybersecurity tools, improving overall security operations through seamless workflows.
- Real-Time Monitoring and Decision-Making
   - Ability to make informed, timely decisions based on real-time security incident data.
   - Enhanced capability to manage and respond to security incidents quickly and effectively, reducing potential damage to the network.

## Acknowledgements
This project combines ideas and methods from various sources, such as the Cybersecurity Tool: LimaCharlie by MyDFIR and my IT experience. These resources provided the fundamental information and techniques, which were then modified in light of practical uses.
 - [MyDFIR](https://www.youtube.com/watch?v=LbXiQnukb6Q)
 - [LimaCharlie](https://app.limacharlie.io)
 - [Kali Linux](https://www.kali.org/)
 - [Windows 10 Eval](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise)

## Disclaimer
The sole goals of the projects and activities here are for education and ethical cybersecurity research. All work was conducted in controlled environments, such as paid cloud spaces, private labs, and online cybersecurity education platforms. Online learning and cloud tasks adhered closely to all usage guidelines. Never use these projects for improper or unlawful purposes. It is always prohibited to break into any computer system or network. Any misuse of the provided information or code is not the responsibility of the author or authors.
