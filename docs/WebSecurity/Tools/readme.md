<div align="center">
<table>
  <!-- Erste Spalte -->
  <td>
    <table>
	<th colspan="4"><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/WebSecurity/" >Web Security</a></th>
      <tr>
        <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/AttackVectors/">
<div><b>Attack Vectors</b></div>
</a></td>
        <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/WebSecurity/AttackTypes">
<div><b>Attacks </b></div>
</a></td>
        <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/WebSecurity/Tools">
<div><b>Tools </b></div>
</a></td>
        <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/WebSecurity">
<div><b>Monitoring&Forensic🚧</b></div>
</a></td>
      </tr>
    </table>
  </td>

  <!-- Zweite Spalte -->
  <td>
    <table>
    <th colspan="3"><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity">Cloud  Security</a></th>
      <tr>
        <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/AttackVectors/#cloud-bases-attack-vectors">
<div><b>Attack Vectors</b></div>
</a></td>
       <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity/Tools">
<div><b>Tools</b></div>
</a></td>
               <td><a href="https://ji-podhead.github.io/Web-And-CloudSecurity/CloudSecurity/Monitoring/">
<div><b>Continious Monitoring 🚧</b></div>
</a></td>
      </tr>
    </table>
  </td>
</table>
</div>


<div align="center">
    <a href="https://github.com/ji-podhead">  
      <img src="https://github.com/ji-podhead/ji-podhead/blob/main/logo.jpg?raw=true" align="right" width="50" />
</a>
</div>

# Web Security

## Tools

#### Automatic Testing
The need for the following Methods can vary based on your Infrastructure.
Automated testing can help you to discover potential risks, whether this depends on permissions, law-violation, or unsecure code and is therefore crucial to Appsec and DevOps.

| Topic                                            | Description |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | 
| ***Unit-Tests***                                 | Verify individual components or modules within a codebase for correctness. Particularly important for microservice development.  |
| ***Automated CodeBase Test's***                  | Use SAST and ACS as part of CI/CD to scan your code for vulnerabilities like a possible Buffer-Overflow as early as possible during the production stage. Github-Actions already implements those.                                                   | 
| ***Integration Tests***                          | Check how various components or services interact. Crucial to ensure interactions between microservices function as expected and do not produce unintended side effects.                                                                             | 
| ***Load and Performance Tests***                 | Simulate high load conditions to evaluate the performance and reliability of cloud and container environments under stress.                                                                                                                          | 
| ***Security Scanning and Static Code Analysis*** | Help identify known vulnerabilities in code and configurations. Tools like OWASP Zap, SonarQube, or Snyk can automatically scan codebases and issue warnings for potential security issues.                                                          | 
| ***Infrastructure as Code (IaC) Testing***       | With many modern cloud infrastructures managed using IaC tools like Terraform, AWS CloudFormation, or Azure Resource Manager, it's essential to test these definitions to ensure they are correct and free from unintended changes or security gaps. | 
| ***Compliance Checks***                          | Compliance checks ensure cloud and container environments comply with relevant standards and regulations. This includes adherence to data protection laws, security policies, or branch-specific standards.                                          | 
| ***Dependency Check***                           | Dependency checks review project dependencies for known security issues. Tools like Retire.js or SLSA (Supply Chain Levels for Software Artifacts) can help ensure the security of used libraries and frameworks.                                         |

---
#### Playgrounds and training

| Project Name     | Description                                                                      | Website                                                                                                                                 |
| ---------------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| DVWA             | Damn Vulnerable Web Application, designed for educational purposes.              | [DVWA](https://www.dvwa.co.uk/)                                                                                                         |
| OWASP Juice Shop | A deliberately vulnerable web application for teaching web application security. | [Juice Shop](https://juice-shop.webapp-security.academy/)                                                                               |
| VulnHub          | Collection of intentionally vulnerable virtual machines for learning purposes.   | [VulnHub](https://www.vulnhub.com/)                                                                                                     |
| Metasploitable   | A purposely vulnerable Linux VM for practicing penetration testing skills.       | [Metasploitable](https://information.rapid7.com/download-metasploitable.html?&utm_source=lb&utm_medium=web&utm_campaign=metasploitable) |
| Hack This Site   | A collection of challenges aimed at teaching computer science and IT concepts.   | [Hack This Site](https://www.hackthissite.org/)                                                                                         |
| TryHackMe        | Interactive learning platform for cybersecurity training and practice.           | [TryHackMe](https://tryhackme.com/)                                                                                                     |

---
#### Analysis, Pentesting and Forensic

| Tool                                                             | Description                                                                                                                                                                                        | Importance                                                                                                                                                       | Capabilities                                                                                                                                                                                                           |
| ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ***[Burp Suite](https://portswigger.net/burp)***                 | A comprehensive web application security testing tool.                                                                                                                                             | Essential for identifying vulnerabilities in web applications, such as SQL injections, cross-site scripting (XSS), and insecure direct object references (IDOR). | Allows for scanning, crawling, and exploiting vulnerabilities in web applications, facilitating the identification and remediation of security issues.                                                                 |
| ***[OWASP](https://owasp.org/)***                                | The Open Web Application Security Project (OWASP) is a community-focused initiative.                                                                                                               | Critical for staying informed about the latest web application security trends and best practices. <br>Offering Tutorials and tools like OWASP ZAP.              | Provides a wealth of resources, including the OWASP Top Ten, which outlines the most critical web application security risks. [OWASP ZAP](https://www.zaproxy.org/) - An open-source web application security scanner. |
| ***[Pale Moon](https://www.palemoon.org/)***                     | A custom-built, community-driven browser.                                                                                                                                                          | Ideal for users seeking a lightweight, customizable browser with enhanced privacy features.                                                                      | Offers a range of customization options, supports a vast array of extensions, and emphasizes privacy and speed.                                                                                                        |
| ***[Wireshark](https://www.wireshark.org/)***                    | A network protocol analyzer.                                                                                                                                                                       | Fundamental for network troubleshooting and analysis.                                                                                                            | Enables the capture and interactive analysis of network traffic, aiding in diagnosing network-related issues and understanding network behavior.                                                                       |
| [***Metasploit*** ](https://www.metasploit.com/)                 | A penetration testing platform.                                                                                                                                                                    | Essential for conducting thorough security assessments and penetration testing.                                                                                  | Facilitates the development and execution of exploit code against targeted systems, helping to uncover vulnerabilities and demonstrate their impact.                                                                   |
| ***[Nmap](https://nmap.org/)***                                  | A network discovery and security auditing tool.                                                                                                                                                    | Key for network mapping and reconnaissance.                                                                                                                      | Automatically discovers hosts and services on a network, creating a map that aids in planning and executing network attacks or defense strategies.                                                                     |
| ***[SQLMap](https://sqlmap.org/)***                              | An automated SQL injection and database takeover tool.                                                                                                                                             | Important for assessing the security of web applications against SQL injection vulnerabilities.                                                                  | Automates the process of detecting and exploiting SQL injection flaws, potentially allowing an attacker to take over a database.                                                                                       |
| ***[John the Ripper](https://www.openwall.com/john/)***          | A fast password cracking tool.                                                                                                                                                                     | Vital for assessing the strength of passwords and identifying weak credentials.                                                                                  | Supports multiple password hash types and is capable of quickly cracking passwords, helping organizations strengthen their security postures.                                                                          |
| ***[Ghidra](https://ghidra-sre.org/)***                          | A software reverse engineering suite.                                                                                                                                                              | Essential for analyzing compiled code to understand its functionality and identify vulnerabilities.                                                              | Supports a wide range of processor architectures and executable formats, enabling deep dives into binary code to uncover hidden logic and security flaws.                                                              |
| ***[Advanced IP Scanner](http://www.advanced-ip-scanner.com/)*** | A free, fast, and powerful network scanner that allows you to see all devices on your network. It scans IP addresses and ports, showing you which devices are online and what services they offer. | Useful for quickly identifying active devices and services within a network, aiding in network inventory and management.                                         | Displays hostnames and MAC addresses of all found devices, making it easier to manage and troubleshoot network issues.                                                                                                 |
| ***[Angry IP Scanner](https://angryip.org/)***                   | Another free network scanner that is lightweight and fast. It can scan IP ranges and display the hostnames and MAC addresses of all found devices.                                                 | Quick and efficient for network administrators to get an overview of connected devices and their status.                                                         | Helps in identifying which devices are online and what services they offer, assisting in network maintenance and security audits.                                                                                      |
| ***[Masscan](https://www.masscan.org/)***                         | A high-speed network scanner that can scan large networks quickly, discovering open ports and services.                                                                              | Essential for rapid network discovery and reconnaissance, providing insights into network topology and potential vulnerabilities.                                   | Can scan entire internet ranges in minutes, supporting a wide range of protocols and providing detailed reports on discovered services and hosts.                                                            |


---
#### forensics-specific 

| Tool           | Beschreibung                                                                                                                                                            | Link                                                |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **Volatility** | A collection of tools for digital forensics, especially for analyzing live systems and crash dump files. It enables extraction of information from a computer's memory. | [Volatility](https://www.volatilityfoundation.org/) |
| **Reveal**     | A GUI-based malware analysis tool that simplifies the reverse-engineering process and facilitates the investigation of malware code.                                    | [Reveal](https://reveal.io/)                        |

---

### Network-Intrusion Detection and Prevention
In IDS, signatures are patterns indicating known attacks or system misuse, from simple data character recognition to complex behaviors. Signature-based IDS alert upon matching predefined patterns, adjustable via scripting languages. This method is easy to understand but requires listing all attack modifications for recognition, increasing the risk of false positives and the need for personnel to analyze alerts.
***Resources:***
[Wiki: Intrusion Detection System](https://de.wikipedia.org/wiki/Intrusion_Detection_System)
 [BSI-Leitfaden zur Einführung von Intrusion-Detection-Systemen](https://www.bsi.bund.de/DE/Service-Navi/Publikationen/Studien/IDS02/gr1_htm.html)
[PaloAlto - What is an Intrusion Detection System?](https://www.paloaltonetworks.com/cyberpedia/what-is-an-intrusion-detection-system-ids)

***Tools***

| Tool         | Description                                                                                                                                                                                      | Link                            |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------- |
| **Snort**    | An open-source Intrusion Detection System (IDS) capable of monitoring network traffic and detecting suspicious activities. Snort can also be configured as an Intrusion Prevention System (IPS). | [Snort](https://www.snort.org/) |
| **Suricata** | Another open-source IDS/IPS that can monitor both network traffic and filesystems. Suricata offers high performance and support for many protocols.                                              |                                 |

---

#### Scraping

| Tool | Description  |Link  |
|----|----------------|------|
| **Beautiful Soup** | A Python library for parsing HTML and XML documents. It creates parse trees that are helpful to extract the data easily. Beautiful Soup transforms a complex HTML document into a tree of Python objects. Can be used along with PaleMoon for dynamic Websites (requires dynmaic webdriver) | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) |
| **Scrapy**         | An open-source and collaborative web crawling framework for Python. It's used for extracting the data from websites, which can then be processed or stored in your preferred structure.   | [Scrapy](https://scrapy.org/) |
| **Selenium**       | A web testing library used to automate browser activities. Selenium tests run directly in a web browser, just as a human user would. It's often used for scraping dynamic content rendered with JavaScript. | [Selenium](https://www.selenium.dev/documentation/en/webdriver/) | **Puppeteer**      | A Node library which provides a high-level API to control Chrome or Chromium over the DevTools Protocol. Puppeteer runs headless by default but can be configured to run full (non-headless) Chrome or Chromium.   | [Puppeteer](https://pptr.dev/) |
| **Requests**       | A simple HTTP library for Python. It allows you to send HTTP requests using Python and handle the response. While not specifically designed for web scraping, it's often used alongside other tools like BeautifulSoup.  | [Requests](https://docs.python-requests.org/en/latest/) | **Pyppeteer**      | A Python port of Puppeteer. Pyppeteer provides a high-level API to control headless Chrome or Chromium browsers. It's useful for scraping dynamic content generated by JavaScript.                                                                                                          | [Pyppeteer](https://miyakogi.github.io/pyppeteer/)                       |
| **Cheerio**        | A fast, flexible, and lean implementation of core jQuery designed specifically for the server. Cheerio parses markup and provides an API for traversing/manipulating the resulting data structure.                                                                                          | [Cheerio](https://cheerio.js.org/)                                       |


---
#### Vulnerability Scanners
A vulnerability scanner is a program that evaluates computers, networks, or applications for known vulnerabilities, identifying weaknesses due to misconfigurations or faulty programming in network assets like firewalls, routers, servers, etc. Modern scanners offer both authenticated and unauthenticated scans, with the former requiring access using remote admin protocols like SSH or RDP and system credentials, allowing detailed OS and software info. Unauthenticated scans may yield many false positives and lack detailed asset information, often used by attackers or analysts to assess external asset security.
***Resources***
[complete list by OWASP](https://owasp.org/www-community/Vulnerability_Scanning_Tools)[wiki: Vulnerability Scanners](https://en.wikipedia.org/wiki/Vulnerability_scanner)

|Tool|Description|
|---|---|
|**OpenVAS**|Part of the Open Vulnerability Assessment System (OVAL), capable of scanning networks for vulnerabilities and generating reports detailing the findings.|
|**Nessus**|A commercial scanner providing detailed information about vulnerabilities in a network. Known for its ability to detect a wide range of vulnerabilities and its extensive database of known vulnerabilities.|
|**Qualys VM**|Similar to Nessus, Qualys VM is a cloud-based scanner identifying vulnerabilities in IT infrastructure. Offers continuous monitoring and prioritization of vulnerabilities based on business risk.|
|**Acunetix**|Detects web application vulnerabilities, finding flaws in HTML, XML, and other web technologies, making it a valuable tool for web application security.|


---
#### Configuration Scanners

| Tool            | Description                                                                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Lynis**       | An open-source security auditing tool for Unix-based systems. Performs an extensive health check of the system, checking for security issues including permissions, processes, file systems, and more.       |
| **Chef InSpec** | A testing framework for infrastructure with a human-readable language for specifying compliance, security, and policy requirements. Allows validation of nodes for compliance, security, and policy as code. |
| **Ansible**     | Primarily an automation tool, but can also be used to assess the state of infrastructure and ensure it meets certain criteria, acting as a form of configuration scanner.                                    |

---
#### DNS Protection

| Feature/Service             | Description                                                                                                                                                                                                                   | Alternatives with Links                                                                                   |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Cloudflare PDNS**         | Not a traditional PDNS service but offers DNSSEC, DDoS protection, and load balancing.                                                                                                                                          | [Cloudflare](https://www.cloudflare.com/)                                                                 |
| **Cloudflare Alternative - Primary DNS** | Using another provider's DNS as your primary DNS. Can be configured for specific needs like privacy or performance.                                                                                                              | [Google Public DNS](https://developers.google.com/speed/public-dns/docs/using), [Quad9](https://quad9.net/) |
| **Cloudflare Alternative - Secondary DNS/Forwarding** | Utilizing a provider's PDNS as your secondary DNS or using forwarding for enhanced security and redundancy.                                                                                                                | [OpenDNS](https://www.opendns.com/), [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)            |
| **Isolate Private DNS Traffic** | Configuring network/firewall rules to route private DNS queries directly to your preferred PDNS recursor, ensuring they do not pass through Cloudflare's public DNS resolver unless necessary.                           | N/A                                                                                                    |
| **Cloudflare DNS Firewall**  | Provides a DNS Firewall for DDoS protection.                                                                                                                                                    | [Censys](https://censys.io/), [AbuseIPDB](https://www.abuseipdb.com/)                                   |
| **Enable DNSSEC Validation** | Enabling DNSSEC on your DNS resolver configuration validates DNS responses against signed records, protecting against DNS spoofing.                                                                                          | [PowerDNS](https://doc.powerdns.com/recursor/dnssec.html), [BIND](https://kb.isc.org/docs/aa-20140219-dnssec-validation-in-bind-9-10) |
| **Cloudflare DDoS Protection** | Offers DDoS protection through load balancing and overcapacity infrastructure.                                                                                                                                  | [AWS Shield](https://aws.amazon.com/shield/), [Akamai](https://www.akamai.com/us/en/security/ddos/protection.jsp) |

---
### Next-Generation Firewalls (NGFWs)

| NGFW Name                                                                                                                                | Description                                                                                                                                                                                               |
| ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ***[Fortinet FortiGate](https://www.fortinet.com/products/next-generation-firewall)***                                                   | Offers high-performance security with integrated network functions, advanced threat protection, and SD-WAN capabilities.                                                                                  |
| ***[Palo Alto Networks Next-Generation Firewall](https://www.paloaltonetworks.com/cyberpedia/what-is-a-next-generation-firewall-ngfw)*** | Provides advanced security features including application visibility and control, user identification, and threat prevention.                                                                             |
| ***[Cisco Meraki MX](https://meraki.cisco.com/solutions/network-security/firewall/)***                                                   | Combines NGFW capabilities with an intuitive dashboard for easy management, offering automatic threat prevention, application control, and flexible deployment options.                                   |
| ***[Sophos XG Firewall](https://www.sophos.com/en-us/products/next-gen-firewall.aspx)***                                                 | Delivers advanced threat protection, application control, and deep packet inspection with a user-friendly interface, high performance, and integrated security features.                                  |
| ***[Check Point SandBlast Zero-Day Protection](https://www.checkpoint.com/products/zero-day-protection/)***                              | Demonstrates the evolution of NGFWs to include advanced threat prevention capabilities, using cloud-based threat intelligence and sandboxing to detect and block unknown threats.                         |
| ***[Juniper Networks SRX Series](https://www.juniper.net/us/en/products/security-services/srx-series-next-generation-firewall.html)***   | Offers a comprehensive NGFW solution with advanced security features, including DPI, application visibility and control, and integrated threat intelligence for high-performance networking environments. |

---
#### DDOS Protection

| Tool                | Description                                                                                                                                                                                                                   | Link                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| **Cloudflare**      | Provides DDoS protection via its global network, leveraging Anycast routing technology to mitigate attacks at the network's edge. Additionally offers rate limiting and page rules for enhanced security measures. | [Cloudflare](https://www.cloudflare.com/ddos-protection/)                         |
| **AWS Shield**      | Amazon's managed DDoS protection service, included at no extra cost with AWS services. Protects applications on AWS with constant detection and automatic inline mitigations, minimizing application downtime and latency. | [AWS Shield](https://aws.amazon.com/shield/)                                      |
| **Akamai Prolexic** | Akamai's enterprise-level DDoS protection service, offering real-time attack detection and mitigation across the Akamai Intelligent Edge Platform. Features automatic attack detection, mitigation, and reporting. | [Akamai Prolexic](https://www.akamai.com/us/en/multimedia/documents/product-sheet/prolexic-rapport-ddos-protection-service.pdf) |
| **Imperva Incapsula** | Offers DDoS protection as part of its wider web application firewall (WAF) and content delivery network (CDN) services. Utilizes machine learning algorithms to detect and mitigate attacks while ensuring website availability. | [Imperva Incapsula](https://www.imperva.com/products/ddos-protection/)                |
| **Radware Alteon**   | Radware's DDoS protection solution focuses on high availability and scalability. Uses advanced analytics and machine learning to detect and mitigate attacks, ensuring uninterrupted access to applications and websites. | [Radware Alteon](https://www.radware.com/products/ddos-mitigation/alteon-ddos-defense/) |
| **Netscout Arbor**   | Specializes in DDoS detection and mitigation, offering real-time visibility into network traffic and automated response capabilities. Part of the larger Netscout family, Arbor provides solutions for large-scale enterprises and service providers. | [Netscout Arbor](https://www.arbornetworks.com/products/arbor-ddos-protection/)     |

