# Cybersecurity Portfolio

## About Me

I am a cybersecurity student with two years of professional experience in automotive information security, and an undergraduate background in network and information security engineering. My interest in this field comes from two things: first, I believe solid cybersecurity work can make a real contribution to protecting people and organisations in the digital world; second, I have always found the process of analysing system weaknesses and fixing vulnerabilities challenging and genuinely rewarding. In my previous role, I worked on compliance audits, Android reverse engineering, vulnerability management, pre-release security testing and incident response for connected vehicle systems. I am now deepening my offensive security skills and working toward a career focused on penetration testing. This portfolio documents my lab work, skill development and ongoing learning progress.

## Technical Skills

### Penetration Testing

- Network scanning & enumeration: Confident (demonstrated in [Nmap Service Scan](projects/nmap-service-scan/))
- Web application vulnerability testing: Confident (SQL injection, XSS, CSRF and other common flaws; practised on DVWA and other training platforms)
- Vulnerability assessment and reporting: Working knowledge
- Virtual lab environment construction: Confident (demonstrated in [Virtual Lab Setup](projects/virtual-lab-setup/))

### Core Tools

- Kali Linux: Confident
- Nmap: Confident
- Wireshark: Working knowledge
- Burp Suite: Confident
- Metasploit Framework: Working knowledge

### Network & Domain Knowledge

- Switch and router configuration: Working knowledge
- Wireless security testing: Basic knowledge
- Automotive cybersecurity and regulatory compliance: Working knowledge
- Machine learning for security use cases: Beginner

## Certifications and Training

I do not currently hold formal industry cybersecurity certifications.

### Training & Ongoing Learning (In Progress)

- Cisco Networking Academy courses (completed as part of university coursework)
- TryHackMe Pre-Security and Complete Beginner learning paths
- Offensive Security OSCP preparation, target completion: Month 12
- WQE7001 Cyber Security coursework, University of Malaya

## Projects

- [Virtual Lab Setup](projects/virtual-lab-setup/) – A fully isolated host-only penetration testing lab built with VMware, Kali Linux and Metasploitable 2.
- [Nmap Service Vulnerability Scan](projects/nmap-service-scan/) – Service version scanning and risk assessment of open ports on a deliberately vulnerable target machine.

## Learning Journey

Taking this cybersecurity course has given me structured hands-on practice and a clearer understanding of professional security workflows. Two specific lab exercises have been the most valuable so far. First, the virtual lab setup assignment taught me how to build a properly isolated testing environment. Before this, I had used virtual machines casually for personal practice, but I did not fully appreciate how critical network isolation is for legal, safe and responsible testing. Learning to configure host-only networking and verify both internal connectivity and external network restriction gave me a standardised process I can reuse for all future lab work. Second, the Nmap service scanning exercise improved my ability to turn raw scan output into meaningful risk assessments. I learned not just how to run a scan, but how to interpret version numbers, match them to known vulnerabilities, and prioritise high-risk services such as outdated FTP and Telnet.

I also ran into a notable problem during separate web testing practice outside of class. I could not capture traffic from a WeChat mini-program using Burp Suite, even after installing the root CA certificate and double-checking system proxy settings. I diagnosed the issue step by step: I verified the proxy listener was active, ruled out basic configuration errors, and eventually realised the mini-program was bypassing the system proxy for certain requests. I resolved it by setting up a second-layer proxy configuration to route all app traffic through Burp reliably. This experience taught me that troubleshooting is often about understanding full traffic flow, not just adjusting tool settings.

One area I still find challenging is implementing machine learning security tools from code. I have worked with pre-built deepfake detection datasets and ready-made models, but writing custom detection scripts or adapting ML algorithms for security use cases is still difficult for me. Advanced exploitation techniques, such as bypassing modern endpoint protection and performing sophisticated privilege escalation, are another area I want to improve in.

My concrete improvement goal is to complete the TryHackMe Offensive Pentesting learning path and compromise 20 active-difficulty machines independently within the next six months, by May 2027. I will measure progress by tracking my completion percentage on the learning path and counting how many machines I can fully compromise without relying on walkthrough hints.

## Career Objective

My target role is a penetration testing engineer, with a long-term interest in combining my existing automotive security experience with offensive testing skills for connected vehicle and web systems. My next three steps to advance toward this goal are clear. First, I will build consistent hands-on practice through TryHackMe and Hack The Box platforms to strengthen my core web and network testing methodology. Second, I will complete the OSCP certification within 12 months to validate my offensive security skills with a widely recognised industry credential. Third, I will expand my knowledge of local regulatory frameworks and cloud security testing to broaden my employability in the Malaysian market, while keeping my automotive security domain knowledge as a professional differentiator.

## Contact Information

- GitHub: [@XDUM-H](https://github.com/XDUM-H)
- LinkedIn: [Dopamine Gnight](https://www.linkedin.com/in/dopamine-gnight-539407443/)
- Email: 1428209845@qq.com
