# DDoS Attacks (Distributed Denial of Service)

A Distributed Denial of Service (DDoS) attack aims to make a system, network, or service unavailable by overwhelming it with traffic from multiple sources.

---

## How DDoS Attacks Work

1. The attacker infects multiple devices (often part of a botnet).
2. These devices send huge volumes of traffic to a target server or network.
3. The system becomes overwhelmed and crashes or becomes unresponsive.

The attack is "distributed" because the traffic comes from many compromised systems across the internet.

---

## Types of DDoS Attacks

### Volume-Based Attacks
Overload bandwidth using massive amounts of data.
- Example: UDP floods

### Protocol Attacks
Consume resources on networking equipment (firewalls, load balancers).
- Example: SYN floods, Ping of Death

### Application-Layer Attacks
Target specific applications (like web servers) with requests that are expensive to process.
- Example: HTTP floods

---

## Signs of a DDoS Attack

- Slow network performance
- Unavailability of websites or services
- Increase in traffic from unusual IP ranges
- Failure of connectivity tests (e.g., ping, traceroute)

---

## Real-World Example

The 2016 Mirai botnet attack targeted DNS provider Dyn, disrupting access to major websites like Twitter, Netflix, and Reddit. The botnet was made up of IoT devices with default credentials.

---

## Defense Against DDoS

- Use a content delivery network (CDN) or DDoS mitigation service
- Apply rate limiting and traffic filtering
- Implement redundancy and load balancing
- Monitor traffic patterns for anomalies
- Disable unused services that may be vulnerable

---

Next: [Insider Threats](insider-threats.md)
