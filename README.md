# new-beginning
 
$in this file am goona write the steps of pentration testing one by one $$
$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1- reconncanceing and scanning :
first of all use>>>
nslookup : nsloolup "target website"
hping3 : hping3 -8 "port-port" -S "website"
ping : ping "target ip or DNS"
dig : dig "target website" ANY #ANY is to show you all DNS info 
whois :whois "DNS server"
nmap : nmap -Sv -Sc -A "target ip"
nikto : nikto -h "target ip or DNS"
netdiscover: netdiscover -i (interface) -P 
osint (phoneinfoga): python3 phoneinfoga.py -n "phone NUM"  # git this tool for GITHUB.
wireshark: it has graphic view 

#summery is to check the TCP & UDP ports if its open or not and gather the 
info about DNS server and MAC address  and the activity of the network and show you if the 
target use firewall or not 

#pay attention before you start your own pentest on in website so you can make sure is not illegal >>>>>
$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
