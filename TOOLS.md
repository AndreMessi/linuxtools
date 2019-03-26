# Full:

Vega

Owasp ZAP

Burp Suite

arachni

Zenmap (nmap)

Extra: Golismero, Grabber

# Enumeration

Gobuster `go get github.com/OJ/gobuster`

# Subdomain Enumeration

curl -s "http://web.archive.org/cdx/search/cdx?url=*.hackerone.com/*&output=text&fl=original&collapse=urlkey" |sort| sed -e 's_https*://__' -e "s/\/.*//" -e 's/:.*//' -e 's/^www\.//' | uniq

Sublist3r | https://github.com/aboul3la/Sublist3r

Amass | `go get -u github.com/OWASP/Amass`

# Subdomain takeover:

subdomain-takeover | https://github.com/antichown/subdomain-takeover

Aquatone | https://github.com/michenriksen/aquatone/releases/  not working on latest feature

knockpy | `pip3 install knockpy`

takeover | https://github.com/ZishanAdThandar/linuxtools

# AWS

Bucket Finder https://digi.ninja/projects/bucket_finder.php

# spider

Blackwidow

# open redirect:

Open Redirect Scanner | https://github.com/ak1t4/open-redirect-scanner

# CSRF

# host header injection

# Clickjack:

clickjacktest

# SQLi

sqlmap

# XSS:

xsspy | https://github.com/ZishanAdThandar/linuxtools

injectX

XSStrike

XSS Radar

# CORS:

# SSRF:

# LFI:

fimap

LFISuite

# RFI:

# RCE

# XXE

XXER | https://github.com/TheTwitchy/xxer




# CTF

1. Stego
   Steghide http://steghide.sourceforge.net/download.php 
   Stegcracker https://github.com/Paradoxis/StegCracker
   Stegsolve http://www.caesum.com/handbook/stego.htm
   OpenStego https://github.com/syvaidya/openstego/releases
   



