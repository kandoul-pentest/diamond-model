# diamond-model
Learn about the four core features of the Diamond Model of Intrusion Analysis: adversary, infrastructure, capability, and victim.
# 🔷 Diamond Model of Intrusion Analysis

The Diamond Model describes a cyber event using 4 core features and 6 optional meta-features.

## 🔹 Core Features

1. **Adversary**  
   - The attacker (individual, group, or entity).
   - Has intent, capability, and access.

2. **Capability**  
   - Tools, skills, and techniques used (e.g., malware, phishing, exploits).
   - Can be:
     - Manual (e.g., password guessing)
     - Advanced (e.g., custom malware)

3. **Infrastructure**  
   - Systems used by the adversary to deliver or control capabilities.
   - Can include:
     - IP addresses, domains, email addresses
     - Type 1: Owned by the adversary
     - Type 2: Controlled by an intermediary (e.g., staging server)

4. **Victim**  
   - The target of the attack (individual, system, or organization).

## 🔹 Meta-Features (Optional)

1. **Timestamp**  
   - Date and time of the event.
   - Helps identify patterns and time zones.

2. **Phase**  
   - Steps in the attack process (based on Cyber Kill Chain):
     1. Reconnaissance
     2. Weaponization
     3. Delivery
     4. Exploitation
     5. Installation
     6. Command & Control
     7. Actions on Objectives

3. **Result**  
   - Outcome of the attack: `Success`, `Failure`, or `Unknown`.
   - Related to CIA Triad: Confidentiality, Integrity, Availability.

4. **Direction**  
   - Flow of attack:
     - Victim-to-Infrastructure
     - Infrastructure-to-Victim
     - Infrastructure-to-Infrastructure
     - Adversary-to-Infrastructure
     - Infrastructure-to-Adversary
     - Bidirectional
     - Unknown

5. **Methodology**  
   - Type of attack: Phishing, DDoS, Port scan, Malware, etc.

6. **Resources**  
   - External assets needed by adversary:
     - Software, Knowledge, Hardware, Credentials, Access, Funds

## 🔹 Key Axioms

- **Axiom 4**: "Every malicious activity contains two or more phases that must be successfully executed in succession."
- **Resource Axiom**: "Every intrusion event requires one or more external resources to succeed."
