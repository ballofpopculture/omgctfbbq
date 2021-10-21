## Open Source Intelligence
"What MAKE of camera shot this picture?" 
`Apple IPhone`

"What MODEL of camera show this picture?"
`Apple IPhone 5`
## Cryptography
`0x73636f7270696f6e` Hex

`c2NyaWJibGU=` Base64

`01110011 01100101` Binary

`iveghny ynxr` Rot-13

`hzuvob lyerlfh xzev` Atbash

`Cair eruSA-0org sgaeudrpesr K-II98.ue cn seYQ3` Railfence (3 rails)

`F daS-eefn  n KZ3eheadty.YI8lta oiwy-Q0. r aI2` Railfence (5 rails)

(key) `qizkwcgqbs` + `Y ln xkv lubj swlzqvkht, A vmzb pjk bbua we ddgs ILQ-GQYU-8026` Vignere
### Stego
`strings | grep flagformat`
Digital Invisible Ink Tool


## Password Cracking
`hashcat -w rockyou.txt` (md5, etc)
`hashcat   hash.txt   -m   0   -a   6   hash.txt   svu.txt   ?d?d` Hit it with a word list, but append 2 digits
`ophcrack` (Windows password dumps)

## Network Traffic Analysis
## Log Analysis
#### (For logs with categories)
Get all and do numeric sort
`cat logfile.log | awk '{print $2}' | sort -n`

Get uniq values in a category (How many ips were there?)
`cat logfile.log | awk '{print $3}' | sort | uniq`

Get how many times did GET/POST run?
`cat logfile.log | awk '{print $6}' | sort | uniq –c`

Split on delim, get specific spot in delim array.  (Then get uniqs) GOOD FOR UNIQUE IPs.
`cat access.log | cut -d " " -f 1 | sort | uniq -c | wc -l `

#### (For nginx logs)



## Wireless Access Exploitation
## Forensics
## Scanning
## Web Application Exploitation
## Enumeration and Exploitation
