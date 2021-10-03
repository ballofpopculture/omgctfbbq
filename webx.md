Web Exploitation Challenges
===============

Source Code Challenges
-----------------------
[example](https://jupiter.challenges.picoctf.org/problem/9670/)

[example2](https://jupiter.challenges.picoctf.org/problem/56830/)

At its simplest this is a "needle in a haystack" type challenge. The flag is on the site somewhere, and you simply have to use the clues to find it.

Tactics
* Start with index, view source and see what other pages are mentioned.
* Check for non-standard (non bootstrap/js library) file loads.
* Are there pages mentioned in the source that aren't mentioned in on the actual site?


Cookies
-----------------------
[cookie example](http://mercury.picoctf.net:64944/)

[cookie example 2](https://jupiter.challenges.picoctf.org/problem/44573/)
Best done with browser extension like [EditThisCookie](http://www.editthiscookie.com/). Early indicator is a cookie with a clear name ("admin", "user", "authorization") and a cleartext value. More advanced versions have an encoded (usually Base64) value that you must decode to find the formatting, then create your own value and encode in Base64.

Tactics
* If the site has a submit button, see how the cookie changes when you submit different values.


Code Analysis/Deconstruction
-----------------------
[example](https://jupiter.challenges.picoctf.org/problem/17682/)

[example 2](https://jupiter.challenges.picoctf.org/problem/17682/)

This tends to be a programming challenge masked as a web exploitation challenge.


Input Hijacking
-----------------------

SQL Injection
-----------------------
[example](https://jupiter.challenges.picoctf.org/problem/39720/)



