# Internship-Elevatelabs-task5

## Task 5  : Capture and Analyze Network Traffic Using Wireshark.

### Objective: 

Capture live network packets and identify basic protocols and traffic types.
 
### Tools:

Wireshark 

### Deliverables:  

A packet capture (.pcap) file and a short report of protocols identified

### Solution:

#### Step 1: 

Install Wireshark. Since I am using kali linux wireshark is pre installed. Select active network interface (usually eth0, wlan0, or similar). To check this I use command ip addr show.

![ipAddr](Screenshots/ipcheck.png)

#### Step 2:

Open Wireshark (GUI). Click Start Capturing Packets (the blue shark fin). Now I Generate Some Traffic

While Wireshark is capturing:

•	Run a ping in the terminal:

![ping](Screenshots/Pingcommand.png)

•	Then I Open a browser and visit website (e.g. www.geeksforgeek.com)

•	Let it run for ~5 minute.

•	Click the red stop button in Wireshark.

#### Step 3:

These are TCP packets with syn flag



These are TCP packets with syn,ack flag

These are TCP packets with ack flag

These are TCP packets with psh,ack flag

Dns- query

Dns- response

Http

ICMP
