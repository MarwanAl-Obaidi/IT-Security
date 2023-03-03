# 20 Network Visibility Quiz

### Which of the following option most accurately describes why visibility is important in the network.

- [ ] Allows the administrator to detect intrusions more easily.
- [X] Allows the administrator to detect intrusion, detect disruptions and manage the network more easily.
- [ ] Allows administrator to manage the network more easily.
- [ ] Allows the administrator to detect disruptions in the network more easily.

### What problems does flow collection pose on a network?

- [X] DoS attacks can be amplified by the mass transportation of flow data during an attack.
- [ ] The flow collection systems are prone to vulnerabilities enabling privilege escalation.
- [ ] Flow data can be easily spoofed to give the flow collector false information about traffic on the network.
- [ ] Flow data can be capture by attackers through a man-in-the-middle attack and used for reconnaissance.

### What is problematic about the Syslog protocol in transporting logs. (2 out of 4)

- [X] Syslog by default uses UDP to send the messages, meaning the logs are not verified to have reached the server.
- [ ] Syslog can be used to execute code which allows attackers to execute malicious code on Syslog servers.
- [X] Syslog uses non-standardized messages which means interpreting the messages is not always easy.
- [ ] Misconfigured Syslog clients can cause errors on the server crashing it.

### Which option explains what a SNMP trap is most accurately.

- [ ] A security feature that stops SNMP managers from changing configurations accidentally.
- [ ] A security feature set when SNMP detects malicious activity on it's agents.
- [X] A trigger set at the agent to send the SNMP manager information when specific requirements are met.
- [ ] A trigger set at the SNMP manager to send information to agents when specific requirements are met.

### Which of the following options accurately describes a problem with SNMP.

- [ ] Attackers can set up rogue SNMP managers to hijack SNMP agents.
- [ ] SNMP uses UDP which makes it so the messages aren't confirmed by agents or managers.
- [X] SNMP packets can be sniffed by attackers giving them information about the network.
- [ ] SNMP managers can easily flooded by SNMP packets to cause a DoS.

### In terms of visibility what does a baseline mean.

- [X] The normal traffic present in the network during normal operation of the network that is referenced when comparing the current traffic.
- [ ] What the network looks like when there is zero traffic on the network.
- [ ] The baseline values for how often the network is under attack that is referenced when comparing the current traffic.
- [ ] How much traffic the network by average can withstand during a DDoS attack.

### What is problematic with implementing a SIEM system to a network?

- [ ] SIEM systems cause a lot of traffic forcing firms to have high quality equipment across the entire network.
- [X] SIEM systems can take up to months to get running properly.
- [ ] SIEM systems are often vulnerable to multiple different attacks.
- [ ] SIEM systems are very inefficient.

### Which of the following options are network taps commonly used for.

- [ ] SNMP
- [X] Packet Sniffing
- [ ] Syslog
- [ ] SIEM

### What are IDS systems used for?

- [X] Analyzing packets for malicious activity, which if triggered are logged and an the administrator alerted.
- [ ] Analyzing protocols for malicious activity, which if triggered are logged and an the administrator alerted.
- [ ] Analyzing packets for malicious activity, which if triggered are blocked and logged.
- [ ] Analyzing protocols for malicious activity, which if triggered are blocked and logged.

### What advantages does flow collection hold over most other logging and monitoring methods?

- [ ] It has centralized collection of the information unlike most other logging systems.
- [ ] It is less prone to vulnerabilities than other logging systems.
- [ ] I allows the administrator to not only log and monitor attacks but configure devices on the fly to combat inturusions.
- [X] It provides visibility of both device information as well as traffic information all across the LAN network.