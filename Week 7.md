# Week 7: Midterm Practical

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to conduct a structured incident investigation and produce a professional report. System processes, services, and network activity were analysed to identify potential security concerns and support evidence-based decision making.

## Screenshot 1 – Process Investigation


<img width="873" height="553" alt="image" src="https://github.com/user-attachments/assets/16493d92-249a-4fec-aac4-27991739d05f" />


### Observation

Running processes were reviewed and sorted according to CPU utilization. The output displayed the most active processes currently executing on the system.

### Explanation

Process analysis is an important incident response activity used to identify suspicious or resource-intensive applications. Unusual processes may indicate malware, unauthorized software, or abnormal system behaviour.

### Result

System processes were reviewed successfully and no obvious anomalies were identified.

## Screenshot 2 – Service Investigation


<img width="955" height="488" alt="image" src="https://github.com/user-attachments/assets/2c15c50c-13d7-4f0c-b4f4-f284763b52d3" />


### Observation

Active services running on the Ubuntu system were displayed successfully. The output included system, networking, printing, and remote access services.

### Explanation

Service analysis helps identify what functionality is active on a system. Security analysts review active services to detect unauthorized software, misconfigurations, or services that may be targeted by attackers.

### Result

Running services were successfully reviewed and documented as part of the incident investigation process.

## Screenshot 3 – Network Investigation


<img width="859" height="411" alt="image" src="https://github.com/user-attachments/assets/b644330b-35c7-41bf-b9e4-74d4560e0b0f" />


### Observation

Active network connections and listening ports were displayed successfully. Both TCP and UDP services were visible in the output, including SSH, DNS, and printing services.

### Explanation

Network investigations focus on identifying active communication channels and services. Open ports can provide insight into system functionality and may reveal potential attack surfaces that require monitoring.

### Result

Network services and listening ports were successfully identified and analysed.

## Screenshot 4 – Incident Summary Evidence


<img width="891" height="508" alt="image" src="https://github.com/user-attachments/assets/8a87c5c9-b37f-4a8e-91bc-b34c04080abc" />


### Observation

Recent system log entries were reviewed using the journalctl utility. The logs contained operating system events, application activity, and user session information.

### Explanation

System logs provide valuable forensic evidence during incident investigations. Analysts use log entries to reconstruct events, identify suspicious activity, and understand what occurred on the host system.

### Result

Recent system activity was successfully reviewed and documented as evidence for the investigation.

## Reflection

This practical combined several investigation techniques used by SOC analysts during incident response activities. Running processes, active services, network connections, and system logs were reviewed to gather evidence and assess the security state of the host.

The investigation demonstrated how information from multiple sources can be correlated to identify suspicious behaviour and support decision-making during security incidents. System visibility is essential for detecting threats and maintaining a secure environment.

## Conclusion

The objectives of this practical were successfully achieved. A structured host investigation was conducted using process analysis, service inspection, network monitoring, and log review techniques. Evidence was collected and analysed to assess the overall security posture of the host system.

The practical highlighted the importance of investigation methodology, evidence collection, and analytical thinking in SOC operations and incident response activities.
