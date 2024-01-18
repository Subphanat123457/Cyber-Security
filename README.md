# Cyber-Security
lerning Cyber Security Basic

## Network(IpV4, IpV6)
IP (Internet Protocol) คือ protocol ที่ใช้

### IPv4
1. Address: 32 bits - 0 to 4294967
2. Subnet mask: Used for dividing network and host part of the address. The
number of "1" in binary representation will determine how many bits are used as
network part. For example, if subnet mask is `255.255.
255.0`, then there are 8 bits for network and 24 bits for
host. In this case, we have a class A network with 16 million addresses.
3. Default gateway: Specifies the router that should be used when sending data
outside the local network.
4. DNS server: Contains the IP address of Domain Name Server which can be used
to resolve domain names into IP addresses.
#### Classful networking
Classful networking was an approach where each device was assigned a class
based on its capacity or functionality. There were three classes: A, B, C.
A class A had 16 million addresses while class B had only 65,53
6 addresses and class C had only 256 addresses. This system made it easier
for devices to identify their own class and know how many addresses they could
possibly use. However, since the introduction of classless networking, all
devices now belong to one class regardless of their actual capability.

### IPv6
IPv6 has a much larger address space compared to IPv4. It uses 12
bytes instead of 4 bytes to represent the address making it more secure.
Addresses in IPv6 look like this:
`2001:db8::/127`
The first part represents the network identifier and the second part
represents the node identifier. Each part consists of 16 hexadecimal digits.
Therefore, an IPv6 address can contain up to 128 bits.

## Firewall
Firewall is a security mechanism designed to control incoming and outgoing traffic at a computer's network
interface. Its main purpose is to filter packets of network data entering and leaving a computer's
operating system. By controlling what types of data pass through the firewall, you can help protect
your computer from malicious activities such as hacking attempts, viruses, Trojan horses, sp
amware, denial-of-service attacks, etc.

## Virtual Private Network (VPN)
Virtual private networks (VPNs) allow users to create a secure connection between two endpoints over
an unsecured communication channel. VPNs provide privacy and security by encrypting the data
being transmitted between the two points. They work by creating a virtual interface between the
two systems, enabling them to communicate as though they were physically connected.

## XSS
Cross-Site Scripting (XSS), also known as cross-site scripting, is
a type of attack that involves injecting scripts into web pages viewed by other users. These scripts
can be run by the browser without the knowledge of the website’s owner, allowing the attacker
to steal information or perform actions on behalf of the user. The goal of an XSS
attack is to exploit vulnerabilities in websites to execute arbitrary code within the context
of the targeted user’s session.

## Sql Injection
Sql injection occurs when an attacker is able to insert SQL commands
into input fields for a database query. An attacker can manipulate these inputs to execute arbitrary
SQL statements with full access to the underlying database. This can lead to unauthorized data
access, modification, or even complete system compromise.

## DNS poisoning
DNS Poisoning is a cybercrime technique where an attacker tricks
individual Internet users into believing that a particular domain name resolves to a specific IP address.
When a victim enters a fraudulent URL containing the maliciously spoofed domain name
(e.g., www.bankofamerica.com), their machine will direct them to
the IP address associated with the fake site rather than the legitimate bank’s server. As a
result, any sensitive information entered into forms on the fraudulent site would be sent directly
to the attackers instead of being delivered to Bank of America.</s>

## DDoS (Distributed Denial of Service) Attacks
A distributed denial-of-service (DDoS) attack is a cybersecurity threat
where multiple computers coordinate to send large amounts of traffic to a single computer or network
in order to make it unavailable to its intended users. DDoS attacks are often carried out
by criminals who seek to disrupt internet services or cause financial loss to businesses. They
often involve flooding a targeted system with traffic in an attempt to overwhelm it so
that normal use becomes impossible.</s>