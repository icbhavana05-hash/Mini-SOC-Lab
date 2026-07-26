# Commands Used

## Ubuntu

### Update

sudo apt update

sudo apt upgrade



### Install Suricata

sudo apt install suricata



### Check Status

sudo systemctl status suricata



### Enable Service

sudo systemctl enable suricata



### Restart

sudo systemctl restart suricata


### View Logs

sudo tail -f /var/log/suricata/eve.json

sudo tail -f /var/log/suricata/fast.log



### Install Splunk

sudo dpkg -i splunk*.deb



### Start Splunk

sudo /opt/splunk/bin/splunk start



### Splunk Status

sudo /opt/splunk/bin/splunk status



## Kali Linux

### Check IP

ip addr


### Host Discovery

nmap -sn <Victim-IP>


### SYN Scan

sudo nmap -sS <Victim-IP>



### Version Detection

sudo nmap -sV <Victim-IP>



### OS Detection

sudo nmap -O <Victim-IP>



### Aggressive Scan

sudo nmap -A <Victim-IP>



### Metasploit

msfconsole
