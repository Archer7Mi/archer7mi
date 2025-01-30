# DNS-Lookup Tools 

DNS (Domain Name System) lookup tools help in gathering domain-related information, including IP addresses, name servers, and registration details. Below are three essential command-line tools used for DNS reconnaissance.

## 1. Nslookup  
**Nslookup** is a command-line tool for querying DNS servers to obtain domain information and IP address information.
It is available in Linux and Windows.

### Usage:
To initiate it, type the nslookup command in a terminal followed by the domain name.
```sh
$ nslookup example.com
```
The manual pages are accessed using the man command. 
```sh
$ man nslookup 
```
## 2. Whois

Whois queries domain registration information to identify where the domain is registered, along with technical contact information and physical location of the hosting service and sometimes the organization itself assuming the organization hosts its own servers.

### Usage:
Whois can be launched from the Linux terminal.
```sh
$ whois example.com
```

Whois can also gather information on IP address ranges assigned to an organization.
```sh
$ whois [ip address]
```


## 3. Dig

Dig functions quite similarly to Nslookup. It also performs DNS queries, however,, unlike nslookup, it only returns the IPv4 address by default.

### Usage:
```sh
$ dig example.com
```

You can perform reverse DNS lookups using Dig.
```sh
$ dig -x [ip address]
```

