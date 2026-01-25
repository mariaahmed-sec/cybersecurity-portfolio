# Network Monitoring and Data Exfiltration Analysis
This document presents applied reasoning on network traffic monitoring, anomaly detection, and indicators of data exfiltration in a detection-and-response context.

## Importance of Network Traffic Monitoring
Monitoring network traffic is crucial in cybersecurity because that is how data travels across systems. Analysts and leads study data using tools such as SIEM, Wireshark, and tcpdump, which help detect and alert on network traffic events and possible threats. These tools are used to analyze indicators related to phishing activity and other suspicious behavior, while prevention and impact reduction are achieved through security controls. Monitoring allows professionals to reduce the threat surface through measures such as access control, least privilege, and other defensive controls.

1. Denial-of-service attacks that can slow down or disrupt normal network traffic.

2. Phishing attacks: Anomalies in the system indicated by multiple-password reset requests or access attempts from unknown IP addresses. These activities are internal and not always confirmed incidents or threats, which is why continuous monitoring is important for filtering normal behavior from suspicious activity.

3. Data exfiltration that causes a large amount of data to be transferred outside the network without authorization.

## Post-Compromise Attacker Behavior
Malicious actors commonly use lateral movement to maintain and expand unauthorized access within a network after an initial compromise. Lateral movement allows them to gather information and keep a low profile until they are ready to extract or export data. Escalating privileges increases their access to highly sensitive data and gives them greater freedom to move data within the network.

## Data Exfiltration Overview

Data exfiltration refers to data leaving the network to an external destination without authorization. This activity can often be detected through unusually large outbound network traffic, especially when it occurs suddenly or during off-peak hours.

Defensive measures against data exfiltration include access control and the principle of least privilege, which limit how much data a compromised account can access. Encryption is also an effective defense because even if data is successfully exported, it cannot be read without the proper decryption key, making the stolen data unusable.

## Key Takeaways

Network traffic monitoring helps identify abnormal activity by analyzing how data moves across a network. Not all events are incidents, but continuous monitoring allows security teams to filter normal behavior from suspicious activity. Controls such as access control, least privilege, and encryption help limit the impact of compromised accounts and reduce the risk of data exfiltration.
