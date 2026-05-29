## Use the NIST Cybersecurity Framework to Respond to a Security Incident

### Overview 
This activity will analyze a network incident using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF), which is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. The analysis uses NIST CSF will help demonstrating a proactive approach to security, improving communication and transparency with stakeholders, and providing best security practices for the organization. 

---

### Scenario
A multimedia company experienced a DoS causing by a flood of ICMP packets, which disrupted internal network services for two hours. The attacker used an unconfigured firewall to overwhelm company network by sending a flood of ICMP pings, which also prevented internal access to network resources. The incident response team responded to the attack by blocking ICMP traffic, stopping non-critical services, and restoring critical network operations.

---

### Apply NIST CSF Framework

#### Summary
The company experienced a security event when network services stopped responding, due to a DDoS attack involving an ICMP flood. The cybersecurity team responded by blocking ICMP traffic, disabling non-critical services, and restoring critical network operations.
#### Identify
The internal network was affected by an ICMP flood attack, disrupting critical network services. 
#### Protect
The cybersecurity team implemented firewall rules to limit ICMP traffic, and an IDS/IPS system to filter suspicious activity.
#### Detect
The cybersecurity team configured network monitoring tools and source IP verification, to identify unusual traffic patterns and fake IP addresses.
#### Respond
The team needs to isolate affected systems, analyze logs, and report the incident to upper managers in the future incidents.
#### Recover
Critical services should be restored first, followed by the restoration of an entire network after the attack was resolved.

---

### What I Learned?
- Clearly identify DoS and DDoS in a security incident: A cybersecurity professional could determine the type of attacks by looking at the scale, impact, and pattern. In this event, the attack was defined as DDoS in the report because the attack affected an entire internal network, all network services stopped responding, and the attackers repeatedly send ICMP packets (flood).
- ICMP flood mitigation techniques: ICMP flood attacks can be reduced by limiting ICMP traffic through the firewall and filtering unusual request patterns.
- Role of firewall, IDS/IPS, and monitoring systems: Firewalls control traffic, IDS/IPS detects and filters suspicious activity, and monitoring systems identify abnormal network behavior.
- NIST CSF framework: The NIST CSF framework helps managing incidents effectively because it is organized into categories of Identify, Protect, Detect, Respond, and Recover.
