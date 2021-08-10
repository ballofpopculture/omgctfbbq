nmap All ports
sudo nmap -p- --min-rate 10000 -v -oA outfile-allports [ip]

nmap specific ports
sudo nmap -sC -sV -oA outfile-speciifcports [ip] -p [port,port,port,port]

