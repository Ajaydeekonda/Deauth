<h1 align="center" id="title">Deauth</h1><br>

<p id="description">Deauth is a script designed to monitor WiFi networks and detect de-authentication attacks. It utilizes packet sniffing and analysis techniques to identify de-authentication attack packets and provide relevant information about the attack. <br><br>This tool can be used by individuals or organizations that are interested in monitoring and protecting their WiFi networks from deauthentication attacks. This tool is particularly useful for:</p><br>

* Network Administrators: Network administrators can use this tool to monitor their WiFi networks for any potential deauthentication attacks. It helps them identify and analyze the attacks, allowing them to take appropriate security measures to protect their network.

* Security Researchers: Security researchers can utilize this tool to study and analyze deauthentication attacks in order to understand their techniques, patterns, and potential vulnerabilities in WiFi networks. This can contribute to the development of stronger security protocols and countermeasures.

* Penetration Testers: Penetration testers can employ this tool as part of their assessment to evaluate the security posture of a WiFi network. By simulating deauthentication attacks, they can assess the network's resilience and identify any weaknesses that could be exploited.

* WiFi Network Owners: Individuals or organizations that operate WiFi networks, such as cafes, businesses, or public places, can utilize this tool to actively monitor their network for deauthentication attacks. It enables them to detect and respond to any malicious activities that could disrupt the network's availability.

* Security Enthusiasts: Security enthusiasts and hobbyists interested in WiFi security can explore and experiment with this tool to gain a better understanding of deauthentication attacks and the techniques used to detect and mitigate them.



<h2> Installation Steps:</h2><br>

```
git clone https://github.com/Ajaydeekonda/Deauth.git
```

```
cd deauthalyzer
chmod +x ./install.sh && ./install.sh
```

```
sudo python deauth.py
```

<br><h2>Usage:</h2>

1\. Run the script with root privileges. <br><br>2. The script will display a list of available WiFi interfaces. Select the number corresponding to the interface you want to use for monitor mode. <br><br>3. The script will start monitoring the selected WiFi interface for de-authentication attack packets. If an attack is detected it will display information about the attack including the source MAC address. <br><br>4. The script will also record the details of detected attacks in a text file. Each attack will be stored in a separate file with the name deauthlog\_dateandtime.txt where dateandtime represents the timestamp when the attack was detected.<br>

  
  


