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

## DoS
Denial of Service (DoS) attacks refer to targeting a system with too many requests from
legitimate users, causing the system to become unable to process new requests. Unlike DDo
S attacks, which aim at making a system unavailable to all users, DoS attacks specifically
target one user or group of users.

## DDoS vs. DoS
While both terms are used interchangeably, there is a subtle difference between DDoS
and DoS. A DDoS attack targets a system globally, while a DoS attack
specifically targets a single user or group of users.</s>

## Phiping 
Phishing is a type of social engineering attack where an attacker deceives victims into providing private
information such as passwords, credit card details, or other sensitive data by posing as a trustworth
entity like a bank, government agency, or a popular website. The goal of phishing is
usually to steal confidential information or install malware on the victim's device.

## Types of Phishing
1. **Email Phishing**: An email phishing attack involves tricking the recipient into
clicking on links or providing personal information through emails. These messages may appear
as though they come from a well-known company or organization and usually contain urgent or important
messages.
2. **Website Phishing**: Website phishing occurs when attackers create fake websites
with identical or near-identical appearances to real ones. Once inside, attackers can
install malware or steal user credentials.
3. **Social Engineering**: This type of phishing relies more on psychological manip
ulation than technology. It uses tactics like baiting people into revealing sensitive informa
tion or convincing them to perform actions that put them at risk. Social engineers might ask qu
estions that seem innocuous but lead to critical information. For example, they might ask "How do
you spell your name?" followed by asking for full names, addresses, phone numbers, etc.
4. **Inside Job**: Inside job refers to situations where employees within a compa
ny or organization collaborate with attackers to carry out a fraudulent activity. Insider
jobs can be more sophisticated and harder to detect compared to traditional phishing attac
ks because the insiders have access to systems and resources.
5. **Wireless Phishing**: Wireless phishing takes advantage of vulnerabilities
in wireless networks. Attackers can intercept Wi-Fi handshakes and capture session keys,
which can then be used to impersonate legitimate devices and gain unauthorized access.
6. **Two-Factor Authentication Bypass**: Two-factor authentication (2FA
or MFA) adds an extra layer of security to protect against phishing attempts. However, some
attacks can still succeed if the attacker has access to the secret key stored in the user’
device or software token. In this case, the attacker needs to find ways to extract the secret
key, often using brute force techniques or exploiting known vulnerabilities in the device
or software.
7. **Targeted Spear Phishing**: Targeted spear phishing focuses on
individuals rather than large organizations. Instead of sending generic phishing emails
to many recipients, attackers aim to reach specific individuals based on their role, interest
or reputation.
8. **Bulk SMS Phishing**: Bulk SMS phishing attacks involve sending
large volumes of text messages to mobile subscribers, often disguised as official
notifications or alerts. These messages are typically sent without the knowledge or consent
of the intended recipients.
9. **Voice Phishing**: Voice phishing works similarly to its SMS
counterpart, except it targets voice communications instead. Attackers use automated voi
ce recognition technologies to mimic authentic calls and trick users into providing sensitive
information over the phone.
10. **Pharming**: Pharming is a method of social engineering where attack
ers manipulate DNS servers so that victims end up accessing fake websites designed to look like trustworthy
ones. The goal of pharming is to deliver malicious content, such as viruses or
malware, to unsuspecting users.</s>

## spam
spam - noun: unwanted advertising or commercial communication; junk mail
### verb: spam
* [third-person singular simple present tense] to send unsolicited commercial messages through
the internet
`The company's email system was being spammed daily.`
### definition:
A term coined by Jargon File contributor Larry Wall to describe any form of electronic communication
that is not wanted, usually due to containing unwanted advertisements or promotional material.
This term is commonly associated with Internet slang and is derived from the acronym "SPAM
(Sun Microsystems Personal And Mass eMail)." It is also sometimes used met
aphorically to refer to any kind of unwelcome message or communication.</s>

## backup type
backup_type - optional parameter specifying the type of backup to create. If omitted, the default
value will be set to `full`. Possible values for `backup_type`:
- `full`: Creates a full backup of all data including databases, files, directories,
and snapshots. This option is suitable when you need to restore everything after a failure.
Full backups take more time and space compared to incremental backups.
- `incremental`: Creates an incremental backup which contains only the changes made since the last
full or incremental backup. This option is suitable if you want to save storage space
since only changed data needs to be stored. Incremental backups require at least one previous
full or incremental backup to function correctly.

## Snapshot
Creating a snapshot before starting a backup job allows you to quickly revert your file
system to a known state in case something goes wrong during the backup process. You can
use this feature to recover your server to a point in time within the retention period.
If you don’t have a specific reason to create a snapshot, we recommend skipping this step
to save resources. Note that creating a snapshot does consume some additional disk I/O.
To enable the creation of a snapshot, include the following line in your backup script:
bash
shell
bash

## VPN
VPN - Virtual Private Network
When using a VPN connection to access your server, it may be necessary to disable SSL
certificate verification in order to connect successfully.

## web allplication firewall
web application firewall (WAF)
Enabling the WAF adds an extra layer of security to your website by filtering out malicious requests
before they reach your web applications. The WAF uses signatures based on known attack patterns
to identify and block potentially harmful traffic. By enabling the WAF, you help protect your
website against various types of attacks such as SQL injection, cross-site scripting (XSS),
and other vulnerabilities. However, keep in mind that the effectiveness of the WAF depends
on how well the rules are written and maintained. We highly recommend consulting with a
security expert to ensure the rules are up-to-date and effective.
Please note that enabling the WAF imposes some performance overhead, so it's best
to do so only if you believe it provides significant value to your site.

## IP Whitelisting / Blacklisting
IP whitelisting allows you to specify trusted IP addresses that are allowed unrestricted
access to your server. These IP addresses bypass any firewall restrictions. Use this feature
if you have legitimate reasons to allow certain IP addresses to bypass the firewall, such
as allowing remote administrative access from trusted internal networks.
On the other hand, IP blacklisting blocks specified IP addresses from accessing your
server altogether. If you suspect someone is trying to hack into your server, adding their
IP address to the blacklist will prevent them from gaining unauthorized access.
Note that both features operate independently; you can add an IP address to either list.
However, it's important not to rely solely on IP whitelisting or blacklisting
for security purposes. It should be used in conjunction with other security measures like firewalls,
strong passwords, and regular system updates.</s>

## MFA
Multi Factor Authentication (MFA) is a method of confirming user identity beyond just username and
password combinations. In the context of CAS, MFA refers to the ability for users to provide
additional authentication credentials when logging into applications. This capability is often
required by financial institutions, telecom providers, and others who need to ensure that only
authorized individuals have access to sensitive data.

## HTTP
The term "HTTP" stands for Hypertext Transfer Protocol. It is one of three core protocol
components that make up the World Wide Web: HTML, CSS, and JavaScript. While the HTTP
protocol itself does not contain any functionality related to user authentication, it serves as
the foundation upon which secure communication between client and server takes place. When
a user navigates to a webpage, makes requests to a server, or receives content from a server
(such as images or style sheets), the browser uses the HTTP protocol. Similarly, when a user
logs into a web application using CAS, the same HTTP protocol is utilized.

## HTTPS
HTTP Secure (HTTPS) is a cryptographic protocol that is built on top of the HTTP
protocol. It adds an additional layer of protection to the communication between a client
(usually a web browser) and a server. The main purpose of HTTPS is to encrypt
communications between a client and a server, ensuring that all information sent over
the network remains confidential. By using HTTPS, even if a malicious actor were able
to intercept the traffic, they would not be able to read or modify the actual content being
sent because the messages are encrypted.

## SSL
Secure Sockets Layer (SSL) is a cryptography standard developed by Netscape
Corporation. SSL provides a way for servers to communicate with clients across an
unsecured network in a secure manner. Although SSL was originally designed primarily for
web browsers, it has since been adopted by many other software systems, including mail
servers, file transfer protocol (FTP) servers, and database management systems.

## STP
Simultaneous Transmission Protocol (STP) is a technology that allows multiple devices
on a local area network (LAN) to transmit data simultaneously without interfering
with each other. This feature helps prevent collisions, where two devices attempt to send
data at exactly the same time, resulting in a loss of data. STP works by delaying
transmissions until there is no conflict with other devices in the network.

## HTP
HyperText Transport Protocol is an umbrella term that encompasses both HTTP and
HTTPS. It refers to the set of rules and procedures that govern how data is transmitted
between a client and a server over the Internet.

