# Week 5: Network Intrusion Analysis

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to use Nmap and Wireshark to identify scanning and reconnaissance activity on a network. These tools assist cybersecurity professionals and SOC analysts in detecting network discovery techniques commonly used before an attack.

## Screenshot 1 – Verifying Nmap Installation


<img width="852" height="217" alt="image" src="https://github.com/user-attachments/assets/6edc587b-12c5-408e-8707-c81afe4bd55b" />


### Observation

The Nmap utility was verified successfully on the Ubuntu system. Version information and compilation details were displayed, confirming that the software was available for use.

### Explanation

Nmap is a network scanning tool used to discover hosts, services, and open ports on a network. Security professionals use Nmap to perform reconnaissance, security assessments, and network audits.

### Result

Nmap was successfully installed and ready for network scanning activities.

## Screenshot 2 – Performing a Basic Nmap Scan


<img width="931" height="297" alt="image" src="https://github.com/user-attachments/assets/5c644123-d70f-4927-bb45-aea6c0439c38" />


### Observation

A basic Nmap scan was performed against the local host (127.0.0.1). The scan identified active services and displayed the state of available ports.

### Explanation

Nmap is used to discover hosts and services on a network. Open ports indicate services that are listening for incoming connections and may require monitoring to ensure they are secure.

### Result

The scan completed successfully. Open services including SSH (port 22) and IPP (port 631) were identified on the target system.

## Screenshot 3 – Capturing Scan Traffic in Wireshark


<img width="945" height="639" alt="image" src="https://github.com/user-attachments/assets/5a268ef8-2a35-4672-907e-9d5442dadf23" />


### Observation

Wireshark successfully captured TCP traffic generated during network communications. The packet capture displayed source and destination IP addresses as well as protocol information.

### Explanation

Wireshark allows analysts to observe network traffic in real time. Reconnaissance activities such as scanning and service identification generate network packets that can be detected and analysed through packet captures.

### Result

TCP network traffic was successfully captured and analysed using Wireshark.

## Screenshot 4 – Analysing Network Reconnaissance Activity


<img width="925" height="276" alt="image" src="https://github.com/user-attachments/assets/77e81908-0289-4ce3-975a-a8e985ebfcff" />


### Observation

A fast Nmap scan was performed against the target system. The scan identified active network services and displayed open ports available on the host.

### Explanation

Reconnaissance is commonly the first stage of a network attack. Nmap is frequently used to identify hosts, discover services, and gather information about target systems. Monitoring this activity helps security analysts identify potential threats before exploitation occurs.

### Result

The scan completed successfully and identified an open SSH service on port 22. This demonstrated how reconnaissance activity can be detected and analysed.

## Reflection

This practical demonstrated how network reconnaissance and scanning activities can be identified using Nmap and Wireshark. Nmap was used to discover active hosts and open ports, while Wireshark provided visibility into the network traffic generated during scanning activities.

Understanding reconnaissance behaviour is important because attackers frequently perform scanning before attempting exploitation. SOC analysts use tools such as Wireshark and log analysis platforms to detect these activities and identify potential threats early.

## Conclusion

The objectives of this practical were successfully achieved. Nmap was used to perform network scans and identify services running on the target system. Wireshark was used to capture and analyse the network traffic generated during the scanning process.

The practical demonstrated how reconnaissance activity appears on a network and highlighted the importance of monitoring scanning behaviour as part of network security operations.
