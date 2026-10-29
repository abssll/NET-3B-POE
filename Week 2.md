# Week 2: Packet Analysis
## Screenshot 1 – Starting Packet Capture


<img width="974" height="692" alt="image" src="https://github.com/user-attachments/assets/8385ee85-5028-490f-ab53-d3ad6a87e9f9" />


### Observation
Wireshark was launched successfully and a packet capture session was started on the enp0s3 network interface. Network traffic was detected and displayed in real time.

### Explanation
Packet capturing is the process of monitoring and recording network communications. Wireshark allows network administrators and security analysts to inspect packets, identify protocols, and analyse network behaviour.

### Result
The packet capture session started successfully, and network traffic was visible on the selected interface.

## Screenshot 2 – ICMP Traffic Analysis


<img width="918" height="635" alt="image" src="https://github.com/user-attachments/assets/d628ccf5-d3f8-42bc-9a58-7630617077c6" />


### Observation
ICMP Echo Request and Echo Reply packets were captured while performing a ping test to 8.8.8.8. The captured packets show successful communication between the Ubuntu virtual machine and the remote host.

### Explanation
The Internet Control Message Protocol (ICMP) is used for network diagnostics and troubleshooting. The ping command sends Echo Request packets to a destination device and receives Echo Reply packets in return. This confirms network connectivity between the source and destination.

### Result
The packet capture confirmed successful communication between the virtual machine and the external network. All requests received corresponding replies, indicating that the network connection was functioning correctly.

## Screenshot 3 – DNS Traffic Analysis


<img width="921" height="592" alt="image" src="https://github.com/user-attachments/assets/04af048f-38ec-48ee-bb69-4dddead80413" />


### Observation
DNS query and response packets were captured while accessing a website through the web browser. The packets show communication between the Ubuntu virtual machine and the DNS server at 8.8.8.8.

### Explanation
The Domain Name System (DNS) translates human-readable domain names into IP addresses. Before a website can be reached, the client must send a DNS query to obtain the IP address of the destination server.

### Result
The DNS server successfully processed the requests and returned valid responses, allowing web resources to be accessed successfully.

## Screenshot 4 – TCP Traffic Analysis


<img width="986" height="583" alt="image" src="https://github.com/user-attachments/assets/ff194dd7-5cf3-4901-9433-86c8f2e6f1b5" />


### Observation
TCP packets were captured during communication between the Ubuntu virtual machine and external network resources. The packet capture displayed source and destination addresses as well as TCP communication details.

### Explanation
Transmission Control Protocol (TCP) provides reliable communication between devices on a network. TCP establishes connections, ensures data is delivered correctly, and manages acknowledgements and retransmissions when necessary.

### Result
The captured TCP packets confirmed successful communication between the client and remote systems. TCP traffic was successfully identified and analysed using Wireshark.

## Conclusion

The objective of this practical was successfully achieved. Wireshark was used to capture and analyse ICMP, DNS, and TCP traffic. The packet captures provided a better understanding of network communication processes and protocol behaviour.

The skills learned in this practical are essential for cybersecurity professionals and Security Operations Centre (SOC) analysts who rely on packet analysis to monitor networks, investigate incidents, and identify potential security threats.
