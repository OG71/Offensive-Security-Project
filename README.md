# Offensive-Security-Project-
My second project completed in UT Austin Cybersecurity Bootcamp. 

The structure of this project was a capture the flag exercise that took place over 3 individual class periods. Once finished, a penetration testing report 
was completed detailing the steps taken during the CTF. 

# Part 1: Web-Application CTF 

For the first section, a fictional, simulated attack was staged against a web-application. 

Reconnaissance methods were used to gain information on the domain such as OSINT, port scanning, etc... 
Attacks were staged such as cross-site scripting, sensitive data exposure, local file inclusion, SQL injections, session management hijacking, directory traversal, 
and other forms of injections. 

Findings from this section were recorded, organized, and placed within the pentest report. 

# Part 2: Linux Server CTF

For the second section, we moved toward exploiting the fictional linux servers of the domain. 

OSINT was used in order to gather information on the server as well as aggressive port scanning. 

Exploitations of the server consisted of using Metasploit (and meterpreter) and using various modules to execute remote code on the servers for initial access, persistence establishment, and privilege escalation. 

# Part 3: Windows Server CTF

For the final section, the Windows servers of the domain were exploited. 

Similarly to previous section, port scans and OSINT methods were used before exploitation to gain initial access. 

Exploitations of the server consisted of similar methods to the Linux side. However, within Metasploit, different modules were used to target different vulnerabilities. Ultimately, we were able to gain initial access, establish persistence, move laterally along the network, and perform a DCSync against the domain controllers to pull credentials and obtain total access to the systems. 

# Part 4: Penetration Test Report 

Below is a link to my pentest report. Feel free to read in order to view detailed steps of the process. 

https://docs.google.com/document/d/16yILgKb6I2RBQ4fx55e5Ge-9Xx3N8K9rEZ7mjeYVuDk/edit?usp=sharing
