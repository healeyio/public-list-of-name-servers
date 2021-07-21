# public-list-of-name-servers
A list of public name servers including DNSCrypt, DoT, and DoH resolvers compiled from different resources into a consumable list for services such as pfblockerng, iptables, firewalld, etc.
## Resources Used
* https://github.com/DNSCrypt/dnscrypt-resolvers
* https://public-dns.info/
* https://dnscrypt.info/public-servers/

## Common Use Cases
* Blocking all traffic to known resolvers which may be used to bypass DNS filtering.
* Blocking IoT devices from bypassing your desired resolvers by using their own.
* Monitoring of endpoints attempting to bypass preferred resolvers as an IOC or potential bad actor.
