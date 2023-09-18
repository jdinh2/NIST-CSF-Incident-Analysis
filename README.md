<p align="center">
  <img src="https://kybersecure.com/wp-content/uploads/2019/04/NIST-wheel-1.png" alt="Google Logo" width="400" height="200" />
</p>


# Incident Report Analysis: NIST CSF Framework

## Summary
This report details an incident involving a DDoS attack on a multimedia company. We apply the NIST CSF framework to analyze the incident and suggest improvements.

## Identify
- **Type of Attack**: DDoS involving a flood of ICMP packets.
- **Systems Affected**: Internal network services, including web design platforms, graphic design tools, and social media marketing platforms.

## Protect
- **Immediate Action Plan**:
  - Implement a firewall rule to limit the rate of incoming ICMP packets.
  - Conduct source IP address verification on the firewall to filter out spoofed IP addresses on incoming ICMP packets.
  - Implement an IDS/IPS system to recognize and filter suspicious ICMP traffic patterns.
  
## Detect
- **Monitoring and Analysis**:
  - Use network monitoring software to detect and alert for abnormal traffic patterns.
  - Establish a system to continuously monitor incoming external ICMP packets, especially from non-trusted IP addresses.
  - Track and log both authorized and unauthorized user activity.
  
## Respond
- **Incident Response Plan**:
  - Containment: Quickly identify the affected areas and isolate them to prevent further spread.
  - Neutralization: Use firewalls and traffic filters to block malicious traffic.
  - Analysis: Utilize network logs, system alerts, and intrusion detection systems to understand the attack's origin and purpose.
  
## Recover
- **Restoration and Recovery Plan**:
  - Systems: Prioritize critical systems for recovery, ensuring that backup data is clean before restoration.
  - Processes: Re-validate network processes, especially those related to ICMP traffic.
  - Data: Restore data from clean backups after ensuring the threat is neutralized.


