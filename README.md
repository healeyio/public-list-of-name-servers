# public-list-of-name-servers
A list of public resolvers (dns servers, name servers, etc.) including DNSCrypt, DoT, and DoH resolvers compiled from different resources into a consumable list for services such as pfblockerng, iptables, firewalld, etc.

## Resources
* https://github.com/DNSCrypt/dnscrypt-resolvers
* https://public-dns.info/
* https://dnscrypt.info/public-servers/

## Common Use Cases
* Blocking all traffic to known resolvers which may be used to bypass DNS filtering.
* Blocking IoT devices from bypassing your desired resolvers by using their own.
* Monitoring of endpoints attempting to bypass preferred resolvers as an IOC or potential bad actor.

## Limitations
* A bad actor could simply create their own resolver to bypass identification from this list.
* This list relies on other lists and is only as accurate as those lists.
* This may break things like IoT or "smart" devices that require features baked-in to their product.  
  * Please report issues with devices.
  * Example: Ring Cameras use Google DNS by default (_src [Ring trying 8.8.8.8](https://twitter.com/healeyio/status/1335385974977691649)_)

## Lists
* [Combined - All known Resolvers](https://github.com/healey.io/public-list-of-name-servers/)
* [DNS Resolvers](https://github.com/healey.io/public-list-of-name-servers/)
* [DoH, DNSCrypt, DoT Resolvers](https://github.com/healey.io/public-list-of-name-servers/)
* [Combined - All known with sources](https://github.com/healey.io/public-list-of-name-servers/)  
  * **_Note: Use only for troubleshooting or identifying where a server originated_**
