Web Exploition Challenges
===============

Source Code Challenges
-----------------------
[example](https://jupiter.challenges.picoctf.org/problem/9670/)
At its simple this is a "needle in a haystack" type challenge. The flag is on the site somewhere, and you simply have to use the clues to find it.

Tactics
* Start with index, view source and see what other pages are mentioned.
* Check for non-standard (non bootstrap/js library) file loads.
* Are there pages mentioned in the source that aren't mentioned in on the actual site?

[example 2](something)


Cookies
-----------------------
[cookie example](http://mercury.picoctf.net:64944/)
Best done with browser extension like [EditThisCookie](http://www.editthiscookie.com/). Early indicator is a cookie with a clear name ("admin", "user", "authorization") and a cleartext value.
