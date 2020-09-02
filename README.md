![Anurag's github stats](https://github-readme-stats.vercel.app/api/?username=RandsX&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
# WordPress Brute Force Login

Install Requirement
-------------------
``` bash
pkg install php
```

Features
--------
* Standard mode or xmlrpc brute force mode
* http and https protocols supported
* Custom HTTP USER AGENT

Usage
-----
* No Wordlist
``` bash
php wp -t site.com -u admin -p admin
```
* Using Wordlist
``` bash
php wp -t site.com -u admin -l pass.txt
```
* Custom User Agent
``` bash
php wp -t site.com -u admin -l pass.txt -g="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.5 Safari/605.1.15"
```
For use the standar mode or xmlrpc mode, this tool auto detect your want brute force mode in url target.

Screenshot
----------
* Help

![Help Pict](https://images2.imgbox.com/fa/71/vs1tiOtZ_o.png)

* Standart Mode Brute Force

![Standart Mode Brute Force](https://images2.imgbox.com/cd/65/1FDcQayq_o.png)

* Xmlrpc Mode Brute Force

![Xmlrpc Mode Brute Force](https://images2.imgbox.com/84/99/VrmsmUXT_o.png)
