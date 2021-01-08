# PersonalPiholeListsPAllebone

I have a list of about 5 million domains being blockes by adding each of the lists below. Primarily this list is to protect users from accessing sites that are dangerous. A allowlist is required when using all the lists as domains get blocked that are valid/needed by users on the network. A allowlist can be found at the end as a suggested allowlist to start with if you would like to avoid starting from scratch. It unblocks things so that they work, and is less concerned with being tracked and more concerned with ensuring users are safe on the network from malicious sites/actors. If privaciy is your primary concern rather than security, then just dont use the suggested allowlist and manage your own from scratch. If you need sites users might use to mostly function, with blocking of ads and malicious sites, and with privacy when it does not break things, then the allowlist is fine to use to begin with and will save you a months work finding everything yourself that general users use on a network. You can then just add more as appropriate as time goes on. It normally takes about a month or so to find all the bits and bobs users use if you start from nothing and allow sites as they crop up. If you want everything locked down and can manage the initial allowlist yourself then just use the blocklists and add users slowly to the filtering.

In addition there is some IP lists for use on your firewalls to block users who attempt to circumvent the internal DNS with brief explanation on how to reroute/redirect DNS requests and log on the firewalls anyone who changes their DNS server, uses DOT, DOH, any other weird stuff they try etc and flag up in the firewall logs so the users can be reviewed and investigated. These lists and instructions are listed after the allowlist.


## Blocklists

https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt

https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt

https://v.firebog.net/hosts/static/w3kbl.txt

https://adaway.org/hosts.txt

https://v.firebog.net/hosts/AdguardDNS.txt

https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt

https://v.firebog.net/hosts/Easylist.txt

https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts

https://v.firebog.net/hosts/Easyprivacy.txt

https://v.firebog.net/hosts/Prigent-Ads.txt

https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt

https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt

https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt

https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt

https://mirror.cedia.org.ec/malwaredomains/immortal_domains.txt

https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt

https://phishing.army/download/phishing_army_blocklist_extended.txt

https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt

https://v.firebog.net/hosts/Shalla-mal.txt

https://gitlab.com/curben/urlhaus-filter/raw/master/urlhaus-filter-hosts.txt

https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt

To be continued... after checking lists up to date.
