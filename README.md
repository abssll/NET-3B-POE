<img width="940" height="653" alt="image" src="https://github.com/user-attachments/assets/14d6d32b-8829-4bfb-b867-1fd4a070af25" /># Week 1 – CyberOps Lab Setup

## Objective
The objective of this lab was to create and verify a virtualized cybersecurity environment using Oracle VirtualBox and Ubuntu Linux.

## Screenshot 1 – Virtual Machine Configuration


<img width="1919" height="931" alt="Screenshot 2026-10-29 113015" src="https://github.com/user-attachments/assets/be40934b-1304-470f-9aa7-d59ff7ceda83" />


### Observation
Oracle VirtualBox was successfully installed and configured. An Ubuntu 64-bit virtual machine named **Linux Ubuntu** was created and configured with 4096 MB of RAM, 4 virtual processors, and a 25 GB virtual hard disk. The machine was in a running state, indicating that the virtual environment was functioning correctly.

### Explanation
Virtualization allows multiple operating systems to run on a single physical computer. In cybersecurity environments, virtual machines provide a safe and isolated platform for testing, analysis, and security investigations without affecting the host operating system.

## Conclusion
The Ubuntu virtual machine was successfully configured and operational. The environment is ready for security analysis, packet capturing, and future CyberOps practical activities.

## Screenshot 2 – Ubuntu Virtual Machine Login Screen


<img width="844" height="634" alt="image" src="https://github.com/user-attachments/assets/bd613420-1247-4807-a519-0607146af1fc" />


### Observation
The Ubuntu virtual machine started successfully and displayed the Ubuntu login screen with available user accounts. This confirmed that the operating system had been installed correctly and was able to boot without errors.

### Explanation
Ubuntu Linux is used in cybersecurity and networking environments because it provides a stable platform for network analysis, security testing, and system administration. Running Ubuntu inside VirtualBox allows practical activities to be performed in an isolated environment without affecting the host operating system.

### Result
The Ubuntu virtual machine launched successfully and was ready for user authentication and further configuration.

## Screenshot 3 – Ubuntu Desktop




<img width="831" height="517" alt="image" src="https://github.com/user-attachments/assets/dea39574-6701-43fb-b96d-91572350a744" />



### Observation
The Ubuntu desktop loaded successfully after authentication. The graphical user interface was fully operational, displaying the application dock, system controls, and desktop workspace.

### Explanation
The successful loading of the Ubuntu desktop confirms that the virtual machine is correctly configured and functioning. Ubuntu provides a secure and stable environment for networking, cybersecurity, and system administration tasks.

### Result
The virtual machine booted successfully and was ready for further configuration and network analysis activities.

## Screenshot 4 – Network Connectivity Verification


<img width="788" height="609" alt="image" src="https://github.com/user-attachments/assets/c22a5ff9-c953-47f5-a377-77413042f86d" />


### Observation
A connectivity test was performed using the ping command to verify communication between the Ubuntu virtual machine and an external network host. Four ICMP echo requests were sent to 8.8.8.8 and all four responses were received successfully.

### Explanation
The ping utility is used to test network connectivity and measure response times between devices. The successful replies indicate that the virtual machine has a functioning network connection and can communicate with external hosts over the Internet.

### Results
- Packets Sent: 4
- Packets Received: 4
- Packet Loss: 0%
- Average Response Time: 8.533 ms

  ## Screenshot 5 – Wireshark Installation and Verification


 <img width="940" height="653" alt="image" src="https://github.com/user-attachments/assets/ffd5542b-e89f-4ff2-a1e0-452eb5bed308" />
 

### Observation
Wireshark was successfully installed and launched on the Ubuntu virtual machine. The application started correctly and displayed the available packet capture sources and monitoring options.

### Explanation
Wireshark is a network protocol analyzer used to capture and inspect network traffic in real time. It is one of the most commonly used tools by network administrators, security analysts, and SOC teams to troubleshoot network issues, investigate suspicious activity, and analyse packet data.

### Result
Wireshark launched successfully and is ready to capture and analyse network traffic generated within the virtual environment.

### Importance in CyberOps
A Security Operations Centre (SOC) analyst uses Wireshark to monitor communications, identify anomalies, investigate security incidents, and gain visibility into network activity. The successful installation ensures the lab environment is prepared for future packet analysis exercises.

### Conclusion
The Ubuntu virtual machine has a stable and operational network connection, making it suitable for cybersecurity and network analysis activities.

