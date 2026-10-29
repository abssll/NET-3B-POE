# Week 6: Host Intrusion Analysis

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to review running processes, active services, and network connections on a Linux host. These activities assist SOC analysts in identifying suspicious activity, investigating compromised systems, and monitoring host security.


## Screenshot 1 – Viewing Running Processes


<img width="940" height="546" alt="image" src="https://github.com/user-attachments/assets/f749bc6e-35f5-4f42-831b-d8ba61bfef16" />


### Observation

Running processes were displayed successfully. The output showed process identifiers (PIDs), CPU usage, memory consumption, and commands currently executing on the system.

### Explanation

Processes are active programs running on a computer. Monitoring running processes helps security analysts identify suspicious applications, excessive resource usage, and potentially malicious activity.

### Result

System processes were successfully displayed and reviewed.

## Screenshot 2 – Viewing Active Services


<img width="945" height="675" alt="image" src="https://github.com/user-attachments/assets/77b87c63-667d-49d9-9220-4f4411b72b65" />


### Observation

Running services were displayed successfully. The output listed active services currently operating on the Ubuntu system, including networking, logging, SSH, and system management services.

### Explanation

Services are background applications that provide essential operating system functionality. Monitoring active services helps analysts identify unauthorized software, unusual activity, and potential security risks.

### Result

Active services were successfully identified and reviewed.

## Screenshot 3 – Viewing Network Connections


<img width="843" height="384" alt="image" src="https://github.com/user-attachments/assets/ee31840b-d7b4-40ba-937d-58f26102a09c" />


### Observation

Active network connections and listening services were displayed successfully. The output showed TCP and UDP protocols, local addresses, listening ports, and network communication endpoints.

### Explanation

Network connections reveal how a host communicates with other systems and services. Monitoring open ports and active connections helps security analysts detect unauthorized services and suspicious activity.

### Result

Active network connections were successfully identified and analysed, providing visibility into host network activity.

## Screenshot 4 – Host Analysis Results


<img width="852" height="186" alt="image" src="https://github.com/user-attachments/assets/da87e50d-022e-4c10-a69c-4aaf4468990f" />


### Observation

SSH-related processes were identified on the system. The output displayed active processes associated with secure remote administration and authentication services.

### Explanation

Reviewing running processes helps security analysts identify active services and detect unauthorized applications. SSH services are important because they provide remote access capabilities and are commonly targeted by attackers.

### Result

SSH-related processes were successfully identified and analysed, confirming that secure remote access services were active on the system.

## Reflection

This practical demonstrated how host-based analysis can be performed using Linux command-line tools. Running processes, active services, network connections, and SSH-related activities were examined to gain visibility into system operations.

Host intrusion analysis is an important skill for SOC analysts because attackers often leave traces through processes, services, and network activity. Regular monitoring helps identify unusual behaviour, detect compromised systems, and support incident investigations.

## Conclusion

The objectives of this practical were successfully achieved. Running processes, active services, network connections, and SSH-related activity were reviewed and analysed. The information collected provided valuable insight into host activity and system behaviour.

The practical demonstrated the importance of host monitoring as part of cybersecurity operations and highlighted how system information can be used to detect and investigate potential security threats.
