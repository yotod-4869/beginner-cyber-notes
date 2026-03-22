## Networking and Addressing
	Types of Networking :
		by Geographical area coverage:
			1. WAN
			2. MAN
			3. LAN
			4. PAN
		by Class:
			5. Class A
			6. Class B
			7. Class C
			8. Class D
			9. Class E
	IP Address 
		there are two types of ips :- IP4 and IP6
		IP4 has : 4 octets in it 
		00000000.00000000.00000000.00000000
		IP6 has 8 16 bits  in it
		0000:0:0:000:0:0:000:0
	Servers and IP classification for classes
	 Class A -> 8 bit Network and 24 bit Hosts
	 Class B -> 16 bit Network and 16 bit Hosts
	 Class C -> 24 bit Network and 8 bit Hosts
###Exercise
1. 0.0.0.0 --> used for default Gateway , but can't be used by hosts
2. 127.0.0.0 --> used for loopback, Class A
3. 128.0.0.0 --> Class B IP
4. 192.16.0.0 --> Class C used for personal public IP addresses
5. 191.255.0.0 --> CLass B IP 
6. 223.255.255.0 --> Class C
7. 225.255.0.0 -->  Class D , used for multicast, but can't be used by users
8. 192.127.31.0 -->Class C
9. 10.1.1.1 --> Class A , used for professional , server Ips
10. 192.168.1.1 --> Class C , used by routers
### OSI Model
**Layer 7: Application Layer**
	This is the only layer that directly interacts with the user. it provides network services to end-user applications (like web browsers or email clients).
- **Function:** Resource sharing, remote file access, and identifying communication partners.
- **Protocols:** HTTP (Web), FTP (File Transfer), SMTP (Email), DNS.
**Layer 6 : Presentation Layer**
	This layer acts as the "translator" for the network. It ensures that data is in a usable format and is where data formatting and code conversion occur.
	**Function:** Data compression, encryption/decryption, and translation (e.g., converting ASCII to EBCDIC).
	- **Examples:** SSL/TLS, JPEG, GIF, MPEG.
	- **Data Unit:** Data.
**Layer 5 : Session Layer**
	This layer manages the "dialogue" between computers. It establishes, maintains, and terminates connections (sessions) between local and remote applications.
	**Function:** Session checkpointing and recovery. It ensures that if a connection is lost, it can resume from the last known point.
	**Protocols:** NetBIOS, RPC, PPTP.
	**Data Unit:** Data.
**Layer 4 : Transport Layer**
	This layer handles **end-to-end** communication and ensures data integrity. It decides how much data to send, at what speed, and where it goes.
	**Function:** Segmentation (breaking data into pieces), flow control, and error correction.
	**Protocols:** **TCP** (reliable, connection-oriented) and **UDP** (fast, connectionless).
	**Addressing:** Uses **Port Numbers** (e.g., Port 80, 443).
	**Data Unit:** Segments (TCP) or Datagrams (UDP).
**Layer 3 : Network Layer**
	The Network Layer is responsible for **host-to-host** addressing and routing. It finds the best physical path for the data to take.
	- **Function:** Routing packets across different networks and logical addressing.
	- **Protocols:** IPv4, IPv6, ICMP (Ping), ARP.
	- **Hardware:** **Routers** operate at this layer.
	- **Addressing:** Uses **IP Addresses**.
	- **Data Unit:** Packets.
**Layer 2 : Data Link Layer**
	This layer provides **node-to-node** data transfer. It handles the physical movement of data across a single link (like a wire or Wi-Fi signal) and checks for errors at the physical level.
	- **Function:** Framing (organizing bits into frames) and physical addressing.
	- **Hardware:** **Switches** and Bridges operate here.
	- **Addressing:** Uses **MAC Addresses**.
	- **Data Unit:** Frames.
**Layer 1 : Physical Layer**
	This is the lowest layer, dealing with the actual hardware and the raw transmission of "ones and zeros" (bits).
	- **Function:** Defining electrical, mechanical, and physical specifications (voltage levels, cable types, pinouts).
	- **Hardware:** Hubs, Repeaters, Cables (Cat5, Fiber), and Network Interface Cards (NICs).
	- **Data Unit:** Bits.

Exercise:  -Top 30 common ports and what kind of attacks can they face?
        -OSI model and what kind of attacks happens in each layer?
		 -Subnetting
		 -TCP vs UDP
Exercise :
CHeck what class the ip is?
check what the subnet mask is ?
check whether private and public?
and finaly check whether it is useable?
u can use python, java,.... !!!