# Splunk Dashboard Queries

## Total Alerts

index=main event_type=alert
| stats count



## Alerts Over Time

index=main event_type=alert
| timechart count



## Top Source IP

index=main event_type=alert
| top src_ip



## Top Destination IP

index=main event_type=alert
| top dest_ip



## Alert Categories

index=main event_type=alert
| top alert.category



## Alert Signatures

index=main event_type=alert
| top alert.signature



## Alert Severity

index=main event_type=alert
| stats count by alert.severity



## Targeted Ports

index=main event_type=alert
| top dest_port


# Dashboard Panels

The Splunk dashboard contains the following visualizations.

1. Total Alerts
2. Alerts Over Time
3. Top Source IPs
4. Top Destination IPs
5. Alert Categories
6. Alert Severity
7. Targeted Ports
8. Attacker to Victim Communication

These panels provide an overview of attack trends, communication flow, targeted services, and intrusion detection events.
