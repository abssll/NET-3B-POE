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
