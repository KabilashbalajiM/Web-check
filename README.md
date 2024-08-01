WebGuardian is a Python-based vulnerability detection tool for web applications. It performs automated checks on the headers of a given URL to identify potential security vulnerabilities. This tool helps developers and security enthusiasts identify common security weaknesses in web applications and take appropriate measures to mitigate them.

![web](https://github.com/user-attachments/assets/ebe6fa66-2867-43c3-b254-83f4c329d7b0)


Features :

Detection of common vulnerability-related headers, such as Server, X-Frame-Options, Content-Security-Policy, X-XSS-Protection, and X-Content-Type-Options.
Identification of Insecure Direct Object References (IDOR) vulnerability.
Detection of potential SQL Injection vulnerabilities.
Check for the presence of a Web Application Firewall (WAF).
Automated tests for Server-side Request Forgery (SSRF) vulnerability.
Detection of Remote Code Execution (RCE) vulnerabilities.
Identification of potential Path Traversal vulnerabilities.

Usage : 
Ensure Python 3 is installed on your system.
Install the required dependencies: pip install -r requirements.txt.
Run the web_guardian.py script: python web_guardian.py.
Enter the URL you want to check for vulnerabilities.
The tool will perform checks and display any detected vulnerabilities or security concerns.
