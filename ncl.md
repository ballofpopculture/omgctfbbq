## Open Source Intelligence
## Cryptography
## Password Cracking
## Network Traffic Analysis
## Log Analysis
#### (For logs with categories)
Get all and do numeric sort
`cat logfile.log | awk '{print $2}' | sort -n`

Get uniq values in a category (How many ips were there?)
`cat logfile.log | awk '{print $3}' | sort | uniq`

Get how many times did GET/POST run?
`cat logfile.log | awk '{print $6}' | sort | uniq –c`

#### (For nginx logs)



## Wireless Access Exploitation
## Forensics
## Scanning
## Web Application Exploitation
## Enumeration and Exploitation
