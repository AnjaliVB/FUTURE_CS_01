# FUTURE_CS_01

<h1>Task 01 - Vulnerability Assessment Report for a Live Website </h1>
<h2>Summary</h2>

The demo website chosen for this task is https://bwapp.hakhub.net/. 
The security assessment identified several misconfigurations that could expose the system to unauthorized access and data compromise while no active exploitation was performed.

<h2>About Bwapp</h2>

bWAPP, or a buggy web application, is a free and open source deliberately insecure web application developed by MME. It helps security enthusiasts, developers and students to discover and to prevent web vulnerabilities. It prepares one to conduct successful penetration testing and ethical hacking projects. "A security testing framework made for educational purposes". it has over 100 different web vulnerabilities and issues!
It covers all major known web bugs, including all risks from the OWASP Top 10 project. The OWASP Top 10 represents a broad consensus about what the most critical web application security flaws are. is an open source PHP application that uses a MySQL database. It can be hosted on Linux/Windows with Apache/IIS and MySQL. It can also be installed with WAMP or XAMPP. Another possibility is to download our bee-box, a virtual machine pre-installed with bWAPP.

<h2>Background</h2>

This exercise aimed to perform Penetration Testing of the Applications in scope to determine if they were vulnerable to attacks and exploitation. The test consisted of manual testing to detect and exploit vulnerabilities. The assessment was conducted to identify the security vulnerabilities in the Application in scope and propose solutions for the project team to remediate the identified vulnerabilities to make the Application more secure.
The Security Assessment was performed between 6th April to 19th April 2026.

<h2>Scope</h2>
Target: https://bwapp.hakhub.net/
Type of Test: Read-only security assessment
Testing Method: Non-intrusive reconnaissance only
Tools Used: Nmap, browser developer tools, public scanners
No exploitation or active attacks were performed.

<h2>Methodology</h2>
The assessment was conducted using publicly available tools and techniques:
<ul>
  <li>Scanning open ports using Nmap</li>
  <li>Technology detection via Builtwith online tool</li>
  <li>Scanning missing headers with securityheaders.com and Nikto</li>
  <li>Vulnerability testing using Owasp Zap</li>
</ul>

<h2>Tools used</h2>
<ul>
  <li>NMAP</li>
  <li>Nikto</li>
  <li>OWASP ZAP</li>
  <li>BuiltWith</li>
  <li>SecurityHeaders.com</li>
</ul>
