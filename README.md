OMGCTFBBQ
===============

> ballofpopculture | 11/17/2020

--------------------------

The beginning of a WTF repo for team OMGCTFBBQ

---------------
# Table of Contents

1. [Have You Tried?](#have-you-tried)
2. [Website Forensics](#website-forensics)
3. [Passwords](#passwords)
4. [Images](#images)
5. [pwn](#pwn)
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

Passwords
-----------------------

* Zip File Cracking
```
fcrackzip -D -p [password file] sample.zip
```

* John the Ripper
```
john --wordlist=[password.lst] hashfile
```

Images
-----------------------

* EOG

Image viewer, allows you to go through a .gif image by image.
```
eog [filename]
```

* ImageMagick

Turn .gif files into a set of images (as numbered files)
```
convert [.gif file] %02d.gif
```

Convert white to transparent
```
convert [filename] -transparent white [new filename]
```

pwn
-----------------------

Steps
* chmod +x
* strings file
* ltrace file
* hopper file
* Binary Ninja?
* objdump -D file | less
