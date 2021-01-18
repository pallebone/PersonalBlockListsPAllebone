# PersonalPiholeListsPAllebone

Note: If you think I am missing any good lists, please let me know so I can add them :)

I have a list of about 5-6 million domains being blocked by adding each of the lists below. Primarily this list is to protect users from accessing sites that are dangerous. An allowlist is required when using all the lists as domains get blocked that are valid/needed by users on the network. An allowlist can be found at the end as a suggested allowlist to start with if you would like to avoid starting from scratch. This is for convenience and if you are happy to start with nothing thats fine too. My list has about 800 entries. It unblocks things so that they work, and is less concerned with being tracked and more concerned with ensuring users are safe on the network from malicious sites/actors. If privacy is your primary concern rather than security, then just dont use the suggested allowlist and manage your own from scratch. If you need sites users might use to mostly function, with blocking of ads and malicious sites, and with privacy when it does not break things, then the suggested allowlist is fine to use to begin with and will save you a months work finding everything yourself that general users use on a network. You can then just add more as appropriate as time goes on. It normally takes about a month or so to find all the bits and bobs users use if you start from nothing and allow sites as they crop up. If you want everything locked down and can manage the initial allowlist yourself then just use the blocklists and add users slowly to the filtering as mentioned.

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

https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-porn/hosts

https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt

https://block.energized.pro/extensions/porn-lite/formats/hosts

https://block.energized.pro/blu/formats/hosts

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext

https://block.energized.pro/unified/formats/hosts

https://raw.githubusercontent.com/oneoffdallas/dohservers/master/list.txt

https://raw.githubusercontent.com/Sekhan/TheGreatWall/master/TheGreatWall.txt   (Last update June 2020... new list needed if replacement can be found).

https://block.energized.pro/spark/formats/hosts

https://block.energized.pro/bluGo/formats/hosts

https://block.energized.pro/basic/formats/hosts

https://block.energized.pro/porn/formats/hosts

https://block.energized.pro/ultimate/formats/hosts

https://block.energized.pro/extensions/xtreme/formats/hosts

https://block.energized.pro/extensions/regional/formats/hosts

https://raw.githubusercontent.com/llacb47/mischosts/master/social/tiktok-block

https://raw.githubusercontent.com/llacb47/mischosts/master/tiktok-hosts

https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt

https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt

https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt

https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt

https://github.com/marcusminus/Orthrus-BlockList/raw/master/hosts.txt

https://www.github.developerdan.com/hosts/lists/tracking-aggressive-extended.txt

https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/hosts.txt

https://raw.githubusercontent.com/smed79/blacklist/master/hosts.txt

https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt

https://raw.githubusercontent.com/mkb2091/blockconvert/master/output/domains.txt

https://badmojr.github.io/1Hosts/Pro/domains.txt

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Ads

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Adult

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Risk

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Scam

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tracking

https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tunnels

https://raw.githubusercontent.com/tg12/pihole-phishtank-list/master/list/phish_domains.txt

https://anti-ad.net/domains.txt

https://raw.githubusercontent.com/Amdromeda/Blocklist-Pi-Hole/master/Ads%20and%20trackers.txt

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts

https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt

https://someonewhocares.org/hosts/zero/hosts

https://raw.githubusercontent.com/vokins/yhosts/master/hosts

https://winhelp2002.mvps.org/hosts.txt

https://v.firebog.net/hosts/neohostsbasic.txt

https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt

https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt

https://v.firebog.net/hosts/Admiral.txt

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts

https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts

https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt

https://raw.githubusercontent.com/Kees1958/W3C_annual_most_used_survey_blocklist/master/TOP_EU_US_Ads_Trackers_HOST

https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt

https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt

https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt

https://v.firebog.net/hosts/Prigent-Crypto.txt

https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt

https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts

https://urlhaus.abuse.ch/downloads/hostfile/

https://v.firebog.net/hosts/Prigent-Malware.txt

https://raw.githubusercontent.com/HorusTeknoloji/TR-PhishingList/master/url-lists.txt

https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser

https://raw.githubusercontent.com/chadmayfield/my-pihole-blocklists/master/lists/pi_blocklist_porn_all.list

https://gitlab.com/The_Quantum_Alpha/the-quantum-ad-list/-/raw/master/For%20hosts%20file/The_Quantum_Ad-List.txt

https://blocklist.cyberthreatcoalition.org/vetted/domain.txt

https://raw.githubusercontent.com/sk-cat/fluffy-blocklist/main/domains

https://blocklistproject.github.io/Lists/abuse.txt

https://blocklistproject.github.io/Lists/ads.txt

https://blocklistproject.github.io/Lists/crypto.txt

https://blocklistproject.github.io/Lists/drugs.txt

https://blocklistproject.github.io/Lists/fraud.txt

https://blocklistproject.github.io/Lists/gambling.txt

https://blocklistproject.github.io/Lists/malware.txt

https://blocklistproject.github.io/Lists/phishing.txt

https://blocklistproject.github.io/Lists/porn.txt

https://blocklistproject.github.io/Lists/ransomware.txt

https://blocklistproject.github.io/Lists/scam.txt

https://blocklistproject.github.io/Lists/tiktok.txt

https://blocklistproject.github.io/Lists/tracking.txt

https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/youtubelist.txt

https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/crowed_list.txt

https://github.com/badmojr/1Hosts/blob/master/Pro/xtra/domains.txt

https://raw.githubusercontent.com/tg12/pihole-phishtank-list/master/full_grav_list/gravity.txt

https://hosts.oisd.nl/

https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt

https://raw.githubusercontent.com/arapurayil/ABL/master/lists/general/blocked_domains.txt

Blocklist list section complete. 111 entries.

## Allowlist:

Please open AllowlistOptional.txt in files above and add these entries to pihole if appropriate.

How to add all in addition to what you already have:

Copy list to notepad++

Remove carridge returns and replace with a space by finding '\r\n' (do not include ' in search) and replacing with a single space.

Notepad++ now has a list of domains with a space between each entry.

Copy this to clipboard. 

On pihole run command 'pihole -w -nr PastedListOfDomainsFromClipboard'

PastedListOfDomainsFromClipboard is the list you copied to your clipboard. Allowlist now has all entries added.  
 

## other stuff etc to be continued as I get time...
