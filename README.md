OMGCTFBBQ
===============

> ballofpopculture | 11/17/2020

--------------------------

The beginning of a CTF repo for team OMGWTFBBQ

---------------
# Table of Contents

1. [Have You Tried?](#have-you-tried)
2. [Website Forensics](#website-forensics)
---------------

Have You Tried?
-----------------------
* file
```
file [filename]
```

* strings
```
strings [filename]
```

Website Forensics
-----------------------

* GoBuster
Scans a site for directories based on a word list (Kali includes a set of gobuster-specific wordlists)
```
gobuster dir -u http://[website] -w <word list location>
```

