# Week 4: Log Analysis

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to investigate authentication logs and identify suspicious events using Linux log analysis techniques. Log analysis assists Security Operations Centre (SOC) analysts in monitoring system activity, detecting unauthorized access attempts, and investigating security incidents.

## Screenshot 1 – Viewing Authentication Logs


<img width="1254" height="766" alt="image" src="https://github.com/user-attachments/assets/5a2ffbc7-33c3-4a1c-ac02-0625520d1583" />


### Observation

Authentication log entries were displayed from the Linux authentication log file. The log contained information related to login sessions, CRON jobs, and administrative actions performed using sudo.

### Explanation

Authentication logs record security-related events such as logins, authentication requests, and privileged commands. These logs help administrators and SOC analysts track system activity and investigate suspicious behaviour.

### Result

Authentication log data was successfully accessed and prepared for further analysis.

## Screenshot 2 – Searching Authentication Logs


<img width="907" height="621" alt="image" src="https://github.com/user-attachments/assets/22f59e4d-64d1-4c43-962c-27c8b29f5ea0" />


### Observation

Authentication log entries containing session information were filtered successfully. The output displayed multiple session opened and session closed events.

### Explanation

Filtering logs allows analysts to focus on specific events of interest. Session records provide information about when users and services start and end authenticated sessions on the system.

### Result

The filtered authentication logs provided useful information about user activity and system processes that could be used during a security investigation.

## Screenshot 3 – Viewing Recent Authentication Events


<img width="909" height="343" alt="image" src="https://github.com/user-attachments/assets/dbaa8e1c-eab3-4483-abf5-b50a20eac1cf" />


### Observation

Recent login activity was displayed using the last command. The output showed user login sessions, system reboots, login screens, and session durations.

### Explanation

The last command reads login history records stored by the Linux operating system. Security analysts use this information to review authentication activity, identify unusual login patterns, and investigate potential security incidents.

### Result

Recent authentication events were successfully displayed and analysed, providing visibility into user access and system activity.

## Screenshot 4 – Log Analysis Results


<img width="879" height="590" alt="image" src="https://github.com/user-attachments/assets/79e286f5-11f3-4621-b393-63a854b5ee99" />


### Observation

Administrative activities were identified within the authentication logs. The output displayed sudo events showing commands executed with elevated privileges and the users responsible for those actions.

### Explanation

Sudo logs provide evidence of administrative actions performed on a system. Monitoring privileged activity is important because attackers often attempt to gain elevated access after compromising a system.

### Result

Privileged user activity was successfully identified and analysed within the authentication logs.

## Reflection

This practical demonstrated how Linux authentication logs can be used to investigate user activity and security-related events. Authentication logs, session records, login history, and sudo activity were examined using command-line tools. These logs provide valuable information that can assist in identifying suspicious behaviour and troubleshooting security incidents.

Log analysis is a critical skill for SOC analysts because system logs often provide the first indicators of unauthorized access, account misuse, or malicious activity within an environment.

## Conclusion

The objectives of this practical were successfully achieved. Authentication logs were accessed, filtered, and analysed using Linux commands. Information relating to user sessions, login activity, and privileged commands was identified and reviewed.

The practical demonstrated the importance of log analysis in cybersecurity operations and highlighted how system logs can be used to support incident investigations and security monitoring activities.
