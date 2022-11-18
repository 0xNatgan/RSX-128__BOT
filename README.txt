DNS de la machine:  cat /etc/resolv.conf
DNS website:        host [domain]
ARP:                /usr/sbin/arp
route:              /sbin/route -n
info réseau:        /sbin/iconfig (alternative pour trouver l'add local de lien:  ip addr ls)
connec en cour:     Netsat
map rapide:         nmap
dns poussés:        Dig
informations ip:    ipcalc [ip]



link :

Trame : https://hpd.gasmi.net/

Calcul de réseau :https://www.site24x7.com/fr/tools/ipv4-sous-reseau-calculatrice.html

calcul CRC: https://www.ghsi.de/pages/subpages/Online%20CRC%20Calculation/index.php

Calcul ipV6 : https://www.site24x7.com/fr/tools/ipv6-sous-reseau-calculatrice.html

FLAG TCP :

ACK : Reception                                 (A en scapy)
SYN : Demande d'etablissement de connexion      (S en scappy)
FIN : interruption de connexion
RST : Reset de paquet ou rejet de la connexion  (R en scappy)
PSH : Données à recevoir tout de suite
URG : paquet à traiter de manière urgente
