# 19 WLAN Security Quiz

### Which of the following choices are the most prone to have their password cracked. (3 out of 5)

- [ ] WPA2-Enterprise AES
- [X] WPA2 PSK
- [X] WEP SKA
- [X] WPA PSK
- [ ] WPA2-Personal AES

### Which authentication method uses a four-way-handshake?

- [ ] Shared Key Authentication
- [X] Pre-SharedKey
- [ ] RADIUS
- [ ] Open System Authentication

### What reason besides disruptions is there for conducting WLAN DoS attacks.

- [ ] To make all the users switch to other devices.
- [ ] There is no other reason besides denying access to their WLAN.
- [X] An attempt to get the users to join a rogue AP setup by the attacker.
- [ ] To make all the users to switch over to using the LAN network.

### How does deauthentication frame DoS work?

- [ ] By sending stations high PN values so they drop packets with a lower PN received from the AP.
- [X] By sending spoofed deauthentication frames to a AP to disconnect the spoofed device.
- [ ] By sending a malformed deauthentication frame to the AP which disconnects all the devices.
- [ ] By sending the AP a replayed or malformed packet that triggers MIC twice.

### Why do DoS attacks using management frames work so effectively?

- [ ] Management frames have root access to the AP.
- [ ] Management frames are authorized by the administrator.
- [ ] Management frames is personalized for each device.
- [X] Management frames are not authenticated or encrypted.

### Which of the following statements describe passive scanning the most accurately.

- [ ] Passive scanning is less stealthy than active scanning.
- [ ] Passive scanning sends probes to stations to so they'll send probe requests to APs
- [ ] Passive scanning sends out probe request in an attempt to get an AP to answer.
- [X] Passive scanning silently listens to probes sent by AP.

### How can a attacker exploit a devices preferred network list (PNL) to launch a Rogue AP attack.

- [ ] DoS users away from password protected WLANs to join their WLAN
- [ ] Change their SSID to the SSID of the one the user usually uses to match with the network on their PNL.
- [ ] Capture packets between the station and the AP to determine what password they use.
- [X] Answer to device probing for networks present on their PNL.

### Which method would an attacker most likely use to get users to join their Rogue AP.

- [X] DoSing their current WLAN and have their rogue AP with a WLAN with the same SSID
- [ ] Attempt to use social engineering to get them to join their WLAN on the rogue AP.
- [ ] Sending them phishing mails to join their WLAN on the rogue AP.
- [ ] Spreading malware that configures the rogue APs SSID as their default WLAN network.

### Which method would a attacker use to capture credentials for a WLAN using WPA2-Enterprise.

- [ ] Steal the credentials by sniffing for packets between the station and the AP.
- [ ] Perform a phishing attack on the users.
- [ ] Attempt to steal a users computer.
- [X] Setup a Rogue AP with a modified RADIUS server to capture login credentials and try to get users to join it.

### Is isolating the building, where the WLAN is supposed to be used, from other RF signals a valid way to mitigate versus attacks?

- [X] True
- [ ] False