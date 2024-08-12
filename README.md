# Penetration Test Demo

## Objective

The objective of this penetration test demo is to demonstrate the exploitation of a SMB (Server Message Block) vulnerability on the target system. The focus is to identify and exploit a weaknesses in this service, gaining unauthorized access, and successfully exfiltrating sensitive data. This demo highlights the critical risks associated with improperly secured network services and underscores the importance of robust security measures in protecting sensitive information from potential threats.

### Skills Learned

- Advanced understanding of network service vulnerabilities and their impact on system security.
- Proficiency in utilizing Metasploit for exploiting SMB vulnerabilities and gaining system access.
- Ability to execute comprehensive penetration tests and simulate real-world attacks on network services.
- Enhanced skills in assessing network services and identifying critical security vulnerabilities.

### Tools Used

- OpenVAS to provide a detailed report on potential threats and known vulnerabilities within the network.
- Metasploit framework, utilized for conducting penetration testing, by running an exploit module against the target machine to simulate a real-world attack.
- John the Ripper tool for password cracking.

## OpenVAS Network Scan
![image](https://github.com/user-attachments/assets/59616d05-ff49-4b3d-8bc8-0ce9ccb57276)
![image](https://github.com/user-attachments/assets/88e27d05-f4c4-4ca7-a681-eb4ee06397e6)
![image](https://github.com/user-attachments/assets/40b0ad0b-c2d2-4873-86cf-4d57ee119925)

## Vulnerability

Every screenshot should have some text explaining what the screenshot is about.

Example below.

## Time of intrusion and connection to victim system

## Data Exfiltration 

## Recommendations

To remediate the vulnerability exploited on the remote system, several key security controls should be implemented. Firstly, it's essential to apply necessary patches and update Samba software to its latest version. Then, strict permissions and access controls must be configured for the ‘user_map script’ to reduce unauthorized access. Following, avoid running Samba with root permissions to reduce attack surface and limit access on the system. Additionally, the implementation of multi-factor authentication on sensitive systems improves the company’s overall security posture as “it operates on the principle that even if one credential becomes compromised, unauthorized users will be unable to meet the second or third form of required authentication” (Secoda, 2024). These measures together strengthen defenses against this exploit ensuring the protection of data against unauthorized access and security breaches.
