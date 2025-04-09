# Advanced Persistent Threats (APTs)

An Advanced Persistent Threat (APT) is a long-term, targeted cyberattack where an attacker gains unauthorized access to a network and remains undetected for an extended period.

APTs are typically carried out by highly skilled, well-funded threat actors, such as nation-states or organized cybercrime groups.

---

## Key Characteristics of APTs

- **Advanced**: Uses custom malware, zero-day exploits, and sophisticated techniques.
- **Persistent**: Maintains ongoing access, often with multiple backdoors.
- **Targeted**: Focuses on specific organizations, industries, or individuals.
- **Stealthy**: Avoids detection using evasion techniques and minimal activity.

---

## APT Lifecycle (Common Stages)

1. **Reconnaissance**  
   Gathering intel about the target through public sources and passive scanning.

2. **Initial Intrusion**  
   Gaining access through phishing, social engineering, or exploiting vulnerabilities.

3. **Establish Foothold**  
   Installing malware or remote access tools to maintain control.

4. **Privilege Escalation**  
   Gaining higher-level permissions to access more sensitive areas.

5. **Lateral Movement**  
   Moving across systems and networks to find valuable data.

6. **Data Exfiltration**  
   Collecting and quietly sending stolen data out of the network.

7. **Maintain Presence**  
   Creating multiple persistence mechanisms to survive detection or resets.

---

## Notable APT Examples

- **APT29 (Cozy Bear)**: Allegedly linked to Russian intelligence. Known for targeting governments and healthcare, including the 2020 COVID-19 vaccine research campaigns.
- **APT28 (Fancy Bear)**: Allegedly behind multiple attacks on political institutions.
- **Stuxnet**: Believed to be created by the U.S. and Israel to sabotage Iran’s nuclear program.

---

## Defending Against APTs

- Implement strong endpoint detection and response (EDR) tools
- Monitor for anomalous behavior with SIEM systems
- Use network segmentation to limit lateral movement
- Apply regular patches and security updates
- Conduct threat hunting and incident response drills

---

You’ve completed the Attacks & Threats section. Next, you can explore:

- [Security Domains](../security-domains/)
- [Defensive Techniques](../defensive-techniques/)
