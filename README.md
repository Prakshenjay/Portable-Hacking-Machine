# Portable-Hacking-Machine
Potable Hacking Machine (Hackathon 5.0 Project)

The Wi-Fi DoS De-Authentication Attack 

The "jamming" we are using, in this context, is one of many possible denial-of-service (DoS) attacks against a Wi-Fi network. Rather than overpowering the signal like a hardware jammer, a software jammer functions by forging network packets to continually request that all devices in range disconnect themselves. The process is described below. 

This attack has the advantage of being effective against any Wi-Fi network, without needing to be authenticated to the network or know the password. 

 

Deauth attacks by exploiting the 802.11 frame control for if a client is associated securely to the AP. The attacker send a series of "deauth" packets spoofing to be the unauthenticated client to the AP and checks to make sure the AP acknowledges that it received the packet. The attacker also send a series of packets to the client pretending to be the AP saying "hey you need to reauthenticate!". Then the client and the AP say "hey, We need to authenticate! you told me you're no longer authenticated! (this is due to the attacker's packets). Then the two reauthenticate  

HOW TO USE 

 

1.  Start the wifi.sh program in your Kali linux. 

 

 

2. Press the enter key to see the list of available wifis. 

 

 

3. Copy the BSSID of the target’s wifi and paste it . 

 

4. Copy the channel no. of the target’s wifi and paste it . 

 

 

5. You will see the list of wifi users in front of you. 

 

 

6. Press enter . 

 

 

7. The wifi network will shut down as long as your terminal is open. 

 

 

 
