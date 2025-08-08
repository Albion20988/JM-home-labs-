#capture a data packet 
-sudo ifconfig
sudo tcpdump -D
sudo tcpdump -i eth0 -v -c5
-i eth0: Capture data specifically from the eth0 interface.
-v: Display detailed packet data.
-c5: Capture 5 packets of data.
tcpdump: listening on eth0, link-type EN10MB (Ethernet), capture size 262144 bytes
