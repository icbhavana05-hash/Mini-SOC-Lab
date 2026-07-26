# Splunk Data Input Configuration

Suricata generates logs in JSON format.

Log File:

/var/log/suricata/eve.json

Splunk monitors this file continuously using the File and Directory data input.

Index:

main

Source Type:

_json

This enables real-time ingestion of Suricata alerts into Splunk for dashboard visualization and analysis.