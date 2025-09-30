# CEP1---Securing-Linux-Servers-Using-Honeypots-and-IP-Blocking
Description

Objective

To deploy a honeypot and configure defensive mechanisms like SSH hardening and automated IP blocking to detect, analyze, and mitigate SSH brute-force attacks on public-facing Linux servers

Problem Statement and Motivation

Real-time scenario:

SecureDefense, a cybersecurity firm managing Linux servers with public IPs, faces frequent SSH brute-force attacks that exploit weak credentials. To combat these threats, SecureDefense deploys honeypots to mimic real servers, capturing attack data to analyze patterns and attacker behaviors.

They enhance security by automating IP blocking using fail2ban, which monitors failed SSH login attempts and blocks attackers after repeated failures. Additionally, they harden SSH configurations by using non-standard ports and limiting login attempts to reduce attack surfaces.

This strategy not only protects client servers but also provides actionable insights to improve intrusion detection systems. By demonstrating proactive cybersecurity measures, SecureDefense strengthens its reputation as a trusted provider, attracting new enterprise clients.

Industry Relevance

The following tools used in this project serve specific purposes within the industry:

1. Honeypots (vsftpd, smbd, httpd, mysql): Decoy systems that mimic real servers to attract attackers, gather data on attack patterns, and improve intrusion detection systems

2. Fail2ban: Automates IP blocking after failed login attempts, effectively reducing brute-force attacks and maintaining server security 3. TCP Wrappers: Controls access by blocking or allowing specific IPs, adding an extra security layer to Linux servers

4. Firewalld: Manages dynamic firewall rules, restricting access to sensitive ports and mitigating brute-force attacks

5. Splunk: Analyzes server logs to identify attack trends and improve threat detection and response

6. OpenSSH: Secures remote access with custom configurations like nonstandard ports and login attempt limits to reduce vulnerabilitie
