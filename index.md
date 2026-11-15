# Cybersecurity Portfolio

## About Me

I am a cybersecurity student with a background in network and information security engineering. My interest in cybersecurity began during my undergraduate studies, where I worked on wireless security experiments, network operations labs, and deepfake detection tasks. I am particularly drawn to offensive security and penetration testing, as I enjoy analysing system weaknesses and finding practical ways to improve security defences. This portfolio documents my hands-on lab work, technical skill development, and career progress as I build expertise in real-world cybersecurity testing.

## Technical Skills

### Penetration Testing

- Network scanning & enumeration: Confident (demonstrated in [Nmap Service Scan](projects/nmap-service-scan/))
- Web application testing: Working knowledge (Burp Suite, XSS testing via DVWA practice)
- Vulnerability assessment: Working knowledge
- Virtual lab construction: Confident (demonstrated in [Virtual Lab Setup](projects/virtual-lab-setup/))

### Core Tools

- Kali Linux: Confident
- Nmap: Confident
- Wireshark: Working knowledge
- Burp Suite Community Edition: Working knowledge
- Metasploit Framework: Working knowledge

### Network & Other

- Switch and router configuration: Working knowledge
- Wireless security testing: Basic knowledge
- Machine learning for security use cases: Beginner

## Certifications and Training

I do not currently hold formal industry certifications.

### Training & Learning Paths (In Progress)

- TryHackMe Pre-Security and Complete Beginner learning paths
- Offensive Security OSCP preparation, target completion: Month 12
- WQE7001 Cyber Security coursework, University of Malaya
- Undergraduate coursework in network security and machine learning, Xidian University

## Projects

- [Virtual Lab Setup](projects/virtual-lab-setup/) – A fully isolated host-only penetration testing lab built with VMware, Kali Linux and Metasploitable 2.
- [Nmap Service Vulnerability Scan](projects/nmap-service-scan/) – Service version scanning and risk assessment of open ports on a deliberately vulnerable target machine.

## Learning Journey

Taking this cybersecurity course has given me structured hands-on practice and a clearer understanding of professional security workflows. Two specific lab exercises have been the most valuable so far. First, the virtual lab setup assignment taught me how to build a properly isolated testing environment. Before this, I had used virtual machines casually, but I did not fully appreciate how critical network isolation is for legal and safe testing. Learning to configure host-only networking and verify both internal connectivity and external access gave me a standardised process I can reuse for all future lab work. Second, the Nmap service scanning exercise improved my ability to translate raw scan output into meaningful risk assessments. I learned not just how to run a scan, but how to interpret version numbers, match them to known vulnerabilities, and prioritise high-risk ports such as outdated FTP and Telnet services.

I also ran into a notable problem during separate web testing practice outside of class. I could not capture traffic from a WeChat mini-program using Burp Suite, even after installing the root CA certificate and checking system proxy settings. I diagnosed the issue step by step: I verified the proxy listener was active, checked for certificate pinning, and eventually realised the mini-program was bypassing the system proxy for some requests. I resolved it by setting up a second-layer proxy configuration to route all app traffic through Burp reliably. This experience taught me that troubleshooting is often about understanding full traffic flow, not just adjusting tool settings.

One area I still find challenging is implementing machine learning security tools from code. I have worked with pre-built deepfake detection datasets and models, but writing custom detection scripts or adapting ML algorithms for security use cases is still difficult for me. Advanced exploitation techniques such as bypassing modern endpoint protections are another area I want to improve in.

My concrete improvement goal is to complete the TryHackMe Offensive Pentesting learning path and solve 20 active-difficulty machines independently within the next six months, by May 2027. I will measure progress by tracking my completion percentage on the learning path and counting the number of machines I can compromise without walkthrough hints.

## Career Objective

My target career role is a penetration testing engineer, specialising in web application and network security testing. My next three steps to reach this goal are structured around skill validation and practical depth. First, I will build consistent hands-on practice through TryHackMe and Hack The Box platforms to strengthen my core testing methodology. Second, I will complete the OSCP certification within 12 months to validate my offensive security skills with an industry-recognised credential. Third, I will expand my knowledge of regulatory compliance and cloud security testing to qualify for roles in the financial services sector, which is a key employer market in Malaysia.

## Contact Information

- GitHub: [@XDUM-H](https://github.com/XDUM-H)
- LinkedIn: [Dopamine Gnight](https://www.linkedin.com/in/dopamine-gnight-539407443/)
- Email: 1428209845@qq.com
