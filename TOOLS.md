# Full:

Vega

Owasp ZAP

Burp Suite

arachni

Zenmap (nmap)

WPScan

droopescan

Extra: Golismero, Grabber

# Enumeration

Gobuster `go get github.com/OJ/gobuster`

# Subdomain Enumeration

curl -s "http://web.archive.org/cdx/search/cdx?url=*.hackerone.com/*&output=text&fl=original&collapse=urlkey" |sort| sed -e 's_https*://__' -e "s/\/.*//" -e 's/:.*//' -e 's/^www\.//' | uniq

Sublist3r | https://github.com/aboul3la/Sublist3r pip3 install sublist3r

Amass | `go get -u github.com/OWASP/Amass`

# Subdomain takeover:

subdomain-takeover | https://github.com/antichown/subdomain-takeover

Aquatone | https://github.com/michenriksen/aquatone/releases/  not working on latest feature `go get github.com/michenriksen/aquatone`

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

clickjacktest https://github.com/ZishanAdThandar/linuxtools

# SQLi

sqlmap `pip3 install sqlmap`

# XSS:

xsspy | https://github.com/ZishanAdThandar/linuxtools

injectX

XSStrike

XSS Radar

# CORS:

# SSRF:

# LFI and RFI:

fimap https://github.com/kurobeats/fimap

LFISuite https://github.com/D35m0nd142/LFISuite


# Template Injection:

https://github.com/epinna/tplmap

# RCE

# XXE

XXER | https://github.com/TheTwitchy/xxer




# Wordlists

1. fuzzdb https://github.com/fuzzdb-project/fuzzdb
2. PayloadsAllTheThings https://github.com/swisskyrepo/PayloadsAllTheThings 
3. SecLists https://github.com/danielmiessler/SecLists


<hr>

# CTF

# Stego
1. Steghide http://steghide.sourceforge.net/download.php 
2. Stegcracker https://github.com/Paradoxis/StegCracker
3. Stegsolve http://www.caesum.com/handbook/stego.htm
4. OpenStego https://github.com/syvaidya/openstego/releases
   

# LINUX (UBUNTU)

1. htop RAM and CPU monitor 

2. hotspotscan https://github.com/ZishanAdThandar/linuxtools

3. TILIX terminal https://gnunn1.github.io/tilix-web/ installation commands (https://blog.programster.org/ubuntu-16-04-install-terminix)

