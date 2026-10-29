# Week 10: Incident Response

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to apply the incident response lifecycle to a simulated attack scenario. System information, logs, processes, and network activity were reviewed to collect evidence and support incident investigation activities.

## Screenshot 1 – Incident Identification


<img width="649" height="241" alt="image" src="https://github.com/user-attachments/assets/2746e11a-54f5-452d-9bb6-10357aa9a5df" />


### Observation

Current user session information was displayed successfully. The output identified active logins and user access activity on the system.

### Explanation

Incident response begins with identification. Understanding which users are logged into a system helps analysts establish a baseline of legitimate activity and detect unauthorized access.

### Result

User session information was successfully collected and reviewed.

## Screenshot 2 – Process Investigation


<img width="949" height="450" alt="image" src="https://github.com/user-attachments/assets/6cb4356b-b9d7-43f5-a66c-11ee883fbb04" />


### Observation

Running processes were displayed successfully. The output showed active applications, process identifiers, CPU usage, memory usage, and process commands.

### Explanation

Process investigation is an important incident response activity. Analysts review running processes to identify suspicious applications, excessive resource consumption, and potential signs of malicious activity.

## Screenshot 3 – Network Investigation


<img width="961" height="354" alt="image" src="https://github.com/user-attachments/assets/5e4fc7a2-e63b-4dd6-8d2b-9a57a0931391" />


### Observation

Active network connections and listening services were displayed successfully. The output showed TCP and UDP ports available on the host system.

### Explanation

Network investigations help analysts identify active services, open ports, and communication pathways. Unexpected ports or services may indicate security concerns that require further investigation.

### Result

Network services and active listening ports were successfully identified and reviewed.

## Screenshot 4 – Incident Response Evidence Summary


<img width="825" height="284" alt="image" src="https://github.com/user-attachments/assets/a162f224-573a-490e-9894-6567cb2624bc" />


### Observation

Recent login activity was reviewed using the last command. The output displayed user sessions, login times, system access records, and reboot information.

### Explanation

During incident response, login history provides valuable evidence that helps analysts determine who accessed a system and when access occurred. This information supports forensic investigations, timeline analysis, and incident reconstruction.

### Result

User access activity was successfully reviewed and documented as evidence for the incident investigation.

## Reflection

This practical demonstrated the incident response lifecycle by gathering and analysing evidence from user sessions, running processes, network activity, and system information. Multiple sources of evidence were reviewed to understand the security state of the host and identify potential indicators of compromise.

Incident response is a critical SOC function because it enables analysts to detect, investigate, contain, and recover from security events. The practical highlighted the importance of evidence collection, log analysis, and structured investigation techniques.

## Conclusion

The objectives of this practical were successfully achieved. User activity, running processes, network services, and system evidence were collected and analysed as part of a simulated incident response exercise.

The practical demonstrated how system and network information can be used to support investigations, identify suspicious activity, and assist Security Operations Centre analysts in responding to security incidents effectively.

### Result

System processes were successfully reviewed as part of the incident investigation process.
