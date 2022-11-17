# STAR-TUNNEL By STAR-TUNNEL ( ENGLISH )
```
* STAR-TUNNEL SLOWDNS SCRIPT
```
```
THIS IS A SCRIPT FOR AUTO INSTALLATION OF SLOWDNS (DNSTT SERVER) WITH:

-SSH
-SSL
-DROPBEAR
```

**DNSTT Script**

## :heavy_exclamation_mark: Requirements

* A Linux-based operating system (Ubuntu) 
* Ubuntu 20.04 Server x86_64 / 18.04 Server x86_64
* Version 8.5 Preffered Ubuntu 20.04 Server x86_64
* It is recommended to use a new or formatted distro

# Installation
```
rm -rf install; apt update; wget https://github.com/starrising321/STAR-TUNNEL/raw/main/install; chmod 777 install; ./install --start

iptables -I INPUT -p udp --dport 5300 -j ACCEPT

iptables -t nat -I PREROUTING -p udp --dport 53 -j REDIRECT --to-ports 5300

lsof -i :5300

```



<ul>
 <li>TELEGRAM CHANNEL: https://t.me/star_jani</li>
 </ul>
 

## :octocat: Credits

1. [@star_jani )
