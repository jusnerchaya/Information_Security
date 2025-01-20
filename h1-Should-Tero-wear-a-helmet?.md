# X)
# Braiterman et al 2020: Threat Modeling Manifesto
Threat modeling -identifies and -fixes security risks in a system by analyzing what can go wrong and how to address it. The Threat Modeling Manifesto values collaboration, continuous improvement, and practical solutions over rigid tools or perfection. Anyone can do it, focusing on early analysis, diverse teams, and proven methods.

# Shostack 2022: What Can Go Wrong?
The video explains that a big part of threat modeling is figuring out what can go wrong in a system. It shows how spotting problems early helps to make systems safer.No need to overcomplicate it; just focus on finding risks. This approach is simple but very effective.

# OWASP CheatSheets Series Team 2021: Threat Modeling Cheat Sheet
Threat modeling helps find and fix security risks in a system early and throughout development. It includes understanding the system, spotting possible problems, and deciding how to handle them like fixing or removing the risk. Teams can improve by working with security experts, getting training, and using tools to make the process easier.

# Infosec scene :EP 30 Shamoon (Virus)


In 2012, Saudi Aramco, the world's largest oil company, suffered a devastating cyberattack by the Shamoon virus, which destroyed thousands of computers. The company undertook massive efforts to restore operations. The attack raised significant concerns about cybersecurity threats to critical infrastructure.


# a) Security hygiene. What basic security practices should everyone follow? Are there some security hygiene practicies that every company or average Joe should follow?

ans:

a)Security Hygiene: Basic Practices

# **For Individuals:

1,Use strong, unique passwords.

2,Enable multi-factor authentication (MFA).

3,Regularly update software.

4,Be cautious with links and attachments.

5,Use a password manager.

6,Backup data regularly.

7,Avoid sensitive activities on public Wi-Fi; use a VPN.

8,Review account activity for suspicious behavior.

9,Enable security alerts.


# **For Companies:

1,Train employees on security awareness.

2,Implement access control with the principle of least privilege.

3,Encrypt sensitive data.

4,Conduct regular security audits and assessments.

5,Develop an incident response plan.

6,Ensure patch management for all systems.

7,Use endpoint protection solutions.

8,Secure remote access with VPNs and strong authentication.

9,Implement data loss prevention (DLP) solutions.

10,Maintain and test backup and disaster recovery plans.







# b) Imaginary Company Threat Model

COMPANY NAME :CLOUDSHARE OY 

# (1) What Are We Working On?

Key Assets: Customer data, encryption keys, API access, employee credentials.

Crown Jewels: Customer data and encryption keys.

Customer Touchpoints: Web portal for accessing and managing data.

Business Goal: Secure data storage, uninterrupted service.



# (2) What Can Go Wrong?

**Risks:**

Data breach: Unauthorized access via compromised API keys (High).

Ransomware attack: Encrypting customer data (High).

Insider threat: Malicious or accidental file tampering (Medium).

DDoS attack: Disrupting customer portal (Medium).

# Threat Actors: Cybercriminals, hacktivists, insiders.



# (3) What Are We Going to Do About It?

**Mitigations:**

Use strong access controls and MFA.

Rotate encryption keys regularly.

Implement firewall, IDPS, and DDoS protection.

Regularly backup and test disaster recovery.

Train employees on security awareness.


# (4) Did We Do a Good Enough Job?

We can do good enough job by Performing regular audits and pentests.
Continuously update threat models.Monitor security metrics.
Conduct post-incident reviews for continuous improvement.
