#1

###A
i. Define the terms baud rate, bit rate and data rate.
Include how they are related?
	
	Data rate - Rate of data transmission (bits per second)
		- same as Bit rate (BPS)
	Braud rate - Rate at which signal levels (modulation) changes (signal elements per second).
	Give an example of a communication channel where 

ii. The bit rate is lower than the baud rate
	 
	 -  ASK maybe?
	 -  or Can not happen?!?
	
iii. The bit rate is higher than the baud rate
explaining why in each case.
	
	 - Manchester encoding (missing explanation)
---
###B
i. How is the source to destination route determined for networks connected via transparent bridges
	
	Bridge records the source address and links in a table
		- if the address is on the same link as source -> do not forward
		- if the link for the destination is kown then forward only on that link
		- otherwise flood -> non-source links.
	
	Connectionless
	
ii. How is the source to destination determined for networks connected via a source routing bridge?
	
	Bridge issues a discovery frame
		- copied down at every link, recording path list.
	Destination chooses route based on discovery frame
	Routing path carried in data frames
	
	Connection-Oriented
	
iii. Explain how a switch differs from a bridge. Include at which layer of the OSI reference model each operates and how the connected networks behave in each case.
	
	Both Bridges and Switches operate at the data link layer.
	
	A switch has many ports in which it operates, each with their own collision domains whereas a bridge has a single collision domain and therefore port. A switch is essentially a multiport bridge.
	
	Bridge
		- segments collision domains, transport or source routing
	
	Switch
		- seperates networks, wire speed bridge with multiple ports.
---
###C

Nodes on a bus-based CSMA/CD network communicate at 10 Mb/s.
i. Explain the requirement for a minimum frame size.

ii. Explain the requirement for a maximum frame size.
If the minimum frame size is 64 bytes and the signal propagation speed in the wire is 200,000,000 metres/sec.

iii. Determine the theoretical maximum length of the cable.

iv. Compare your answer to ii) with the recommended maximum length for IEEE 802.3 (Ethernet) which is 2,500m. Explain the apparent disaparity.

----
#2
