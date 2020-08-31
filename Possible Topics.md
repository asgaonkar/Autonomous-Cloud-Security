# Possible Topics

Below listed are some possible topics we can focus on!


## Top Threats to CLoud Computing

Page 16 of [Paper](http://www.di.ubi.pt/~mario/artigos/2013-IJIS.pdf)

```
Data Breaches
Data Loss
Insufficient identity, credential and access management
Insecure interfaces and APIs
System vulnerability
Account or service hijacking – using stolen passwords
Insecure Interfaces and APIs
Denial of Service (DoS)
Malicious Insiders
Abuse of Cloud Services
Insufficient Due Diligence
Shared Technology Vulnerabilities
Misconfiguration and inadequate change control
Lack of cloud security architecture and strategy
Insufficient identity, credential, access and key management
Account hijacking
Weak control plane
Metastructure and applistructure failures
Limited cloud usage visibility
```

### General Secuirty Requirements

```
Identification and Authentication
Authorization 
Confidentiality
Non-repudiation 
Availability
Integrity
```

## Summary of the security issues 

### Domains

1. cloud computing architectural framework
1. governance and enterprise risk management
1. legal and electronic discovery
1. compliance and audit
1. information lifecycle management 
1. portability and interoperability
1. traditional security, business continuity and disaster recovery
1. data center operations
1. incident response
1. application security
1. encryption and key management 
1. identity and access management 
1. virtualization 
1. S<sub>ec</sub>aaS (Security as a Service)


### Software

> *Platforms and Frameworks*

```
isolation, resource accounting, safe thread termination
insecure system calls and deficient memory isolation
bad SDLC Approaches
```

> *User Frontend*

```
Internet exposure of frontend interfaces 
deficient configurations, unauthorized access 
application loopholes, masked code injection 
VMM management consoles vulnerabilities 
programmers beliefs 
open-source software, reverse engineering
```

### Storage and Computing

> *Data Storage*
```
collaborative online cloud storage
loss of control
pooling, data locality
multi-location 
integrity checking complexity
```

> *Unreliable Computing*
```
top-down SLAs call stack tightening
malicious agents, downtimes, slowdowns
dishonest computing, administrative
errors in backups, restores or migrations
lack of security in computing models
```

> *Availability*
```
bogus resource usage
cloud outages
```

> *Cryptography*
```
insecure obsolete cryptography, poor key management
faulty cryptographic algorithms
brute-force, dictionary and rainbow tables attacks
```

> *Sanitization*
```
deficient implementation of data destruction policies
non-wiped hard disk discard 
hard disk multi-tenant usage
resources recycling 
```

> *Malware*
```
signature-based anti-viruses effectiveness
cloud malware syncing
```

### Virtualization

> *Managing Images*
```
large-sized images cryptographic overhead
image theft and code injection
dormant and overlooked image repository
VM transience
VM sprawl
```

> *Monitoring Virtual Machines*
```
VMM single point of failure or maliciousness, untrusted VMM components, transparent VMM-based rootkits, lack of monotonicity
VMM isolation, inspection and interposition
VM escape 
VM diversity, VM monitoring overhead
VMM zero-day vulnerabilities
```

> *Virtualized Networking*
```
twofold traffic, limited access and network tailoring, inapplicability of standard security approaches
network security devices effectiveness in virtual networks
unstable network characteristics 
VMs adapters promiscuous mode 
packet sniffing and spoofing
virtual devices software vulnerabilities
virtualized communication channels
```

> *Mobility*
```
VM cloning
VM mobility
propagation of erroneous configurations
live VM migration MitM attack
TOCTTOU vulnerability and replay attack
```

> *VM-Level*
```
VM hopping, cross-VM attacks
side-channel attacks
covert-channel attacks
VM data exfiltration attacks
memory deduplication exploits
malware injection
entropy generation strength
entropy depletion
VM reset vulnerabilities, randomness re-usage
```

> *Malware*
```
VM rollback
malware evasion techniques
malware spreading onto VMs
metamorphic engines
```

> *Availability*
```
bogus VM usage, VMMs capacity to handle VMs
```

### Internet and Services

> *APTs and Malicious Outsiders*
```
intelligence gathering, publicly
available information, reconnaissance scans
doxing
state-sponsored malicious cyber activity, espionage, data exfiltration
hacktivism 
```

> *Protocols and Standards*
```
vulnerable communication protocols, network-based cross-tenant attacks
session riding or session hijacking
mixed HTTP and HTTPS data streams
bad randomness usage in cryptographic keys
cookie theft, cookie poisoning, impersonation attacks
TLS attacks, cookie theft
```

> *Web Services*
```
HTTP statelessness, APIs transaction support for integrity
metadata spoofing attacks, WSDL documents dynamics
XML SOAP wrapping attacks
WSDL scanning
```

> *Web Technologies*
```
infected websites growth
XSS vulnerabilities
injection, broken authentication and session management
HTML hidden field manipulation attack
watering hole attacks, drive-by malware downloads, plugin and browser vulnerabilities
MitB attacks
```

> *Availability*
```
bandwidth under-provisioning, VPSes bots
direct and indirect DoS, race in power
UDP uplink flood attack
resource exhaustion attacks
XML flooding attacks
DNS reflection and amplification attack
Internet and Services
mobile API consumption 
```

### Network

> *Mobile Platforms*
```
mobile malware growth
mobile vulnerabilities growth
rooting and jailbreaking, rootkits, privilege escalation
untrusted underground application distribution channels
cloud syncing mobile applications vulnerabilities
```

> *Perimeter Security*
```
static network infrastructures
boundary-less network perimeter
DMZ assumption
firewalls new incoming connections limit
VMM network sniffing and spoofing
insufficient logging and monitoring capabilities
```

### Access

> *Physical Access*
```
malicious insiders
malicious sysadmins
cold boot attacks, hardware tampering
```

> *Credentials*
```
LDAP and AD servers location, IT management overhead
weak credential-reset vulnerability 
phishing, keyloggers, man-in-in-the-middle attacks malicious redirects, replay sessions
U2R attacks
```

> *Authentication*
```
archaic static password
inapplicability of alternative password schemes
SAML vulnerabilities
XML SAML wrapping attacks
Q&A vulnerabilities
account lockout
```

> *Authorization*
```
centralized access control inapplicability, data mashups
malicious third-party applications
insufficient or faulty authorization checks, frontend interfaces coarse authorization control models
URL-guessing attacks
```

> *Identity Management*
```
synchronization leakage, federated idM trust and validation
complex and fine-grained synchronization
distinct identity tokens and negotiation protocols
```

> *Anonymization*
```
hidden identity of adversaries
de-anonymization attacks
```

### Trust

> *Moving to the Cloud*
```
enterprise nullified trust model [13] 
cloud environments openness
```

> *Human Factor*
```
employees trustworthiness
password sharing
password commonness and strength
social engineering
phishing and spear-phishing
```

> *Reputation*
```
reputation isolation
fate-sharing
```

> *Auditability*
```
providers willingness in providing status information
providers reports trustworthiness
jurisdictional audits, court systems
data locality
lack of privacy-capable audit techniques
```

> *Anonymization*
```
logs anonymization
```

### Compliance and Legality

> *Forensics*
```
public clouds, data locality, data scattering through servers, legal authority, cross-platform forensic techniques
data collection, collation and verification
data seizing and disclosure, hardware confiscation, e-discovery
forensic data unsoundness rendering due to virtualization
encryption schemes, lack of validation for disk images, evidence reliability for jurors
evidence acquisition
```

> *Acts*
```
outdated acts
privacy breaking acts
```

> *Legal Problems*
```
data jurisdictional borders
SLA violation
providers compliance evidences
providers and customers differently aligned interests, transitive nature
SLAs consistency and trustworthiness
data lawful interception
```

> *Accountability*
```
under-attack QoS properties
FRC and EDoS attacks
unreliable computing, protocol violation
inaccurate billing
```

> *Governance*
```
vendor lock-in
data migration, price increases, reliability and security problems, service termination, providers business termination 
race-to-the-bottom
```

