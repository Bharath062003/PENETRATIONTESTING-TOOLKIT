#PENETRATION TESTING TOOLKIT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BHARATH B M

*INTERN ID*: CTIS6523

*DOMAIN*: CYBER SECURITY & ETHICAL HACKING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

DESCRIPTION:
  The Penetration Testing Toolkit is a Python-based software application developed to perform basic security testing on computer systems and networks. Penetration testing, also known as ethical hacking, is a controlled and authorized process of identifying vulnerabilities in a system before they can be exploited by malicious attackers. This toolkit is designed primarily for educational purposes, helping students and beginners understand the fundamental concepts of cybersecurity and system protection.

The toolkit follows a modular design, where each functionality is implemented as a separate module. This structure improves the maintainability and scalability of the project, allowing developers to easily add or modify features. The application is built using Python due to its simplicity, readability, and strong support for networking and security-related libraries. The toolkit operates through a command-line interface, making it lightweight and easy to use.

One of the key modules in the toolkit is the Port Scanner, which is used to identify open ports on a target system. Open ports indicate active services running on a machine, and these services may contain vulnerabilities. By scanning a specified range of ports, the module helps in detecting potential entry points for attackers.

Another important module is the Hash Cracker, which demonstrates how hashed passwords can be cracked using dictionary-based techniques. This module takes a hash value as input and compares it against a list of commonly used passwords to find a match. It highlights the risks associated with weak passwords and the importance of using strong encryption methods.

The Password Strength Checker module evaluates the strength of user-defined passwords. It checks whether the password meets security criteria such as minimum length, inclusion of uppercase and lowercase characters, numbers, and special symbols. This module helps users understand how to create strong and secure passwords to protect their accounts.

The File Integrity Checker is another crucial component, which uses cryptographic hashing (such as SHA-256) to verify whether a file has been modified. By generating and comparing hash values, this module ensures data integrity and helps detect unauthorized changes in files.

Additionally, the toolkit includes a Subdomain Scanner, which identifies active subdomains associated with a given domain. Discovering subdomains is important because they may host different services and could expose additional vulnerabilities in a system.

Despite its usefulness, the toolkit has certain limitations. It performs only basic-level testing and does not include advanced penetration techniques such as exploitation or privilege escalation. It is intended strictly for educational and ethical use, and users must ensure they have proper authorization before testing any system.

In conclusion, the Penetration Testing Toolkit is a practical and educational project that demonstrates essential cybersecurity concepts. It provides hands-on experience in vulnerability assessment, password security, and network scanning. This project not only enhances technical skills but also promotes awareness about ethical hacking and responsible use of technology. Future improvements may include adding a graphical user interface, implementing multi-threading for faster scanning, and generating automated security reports.

OUTPUT:
   ==== Python Penetration Testing Toolkit ====

1. Port Scanner
2. Hash Cracker (Dictionary Based)
3. Password Strength Checker
4. File Integrity Checker
5. Subdomain Scanner
6. Exit
Select an option: 1
Enter target IP: 127.0.0.1
Start Port: 20
End Port: 100

Scanning 127.0.0.1...

==== Python Penetration Testing Toolkit ====

1. Port Scanner
2. Hash Cracker (Dictionary Based)
3. Password Strength Checker
4. File Integrity Checker
5. Subdomain Scanner
6. Exit
Select an option: 2
Enter MD5 hash: 5f4dcc3b5aa765d61d8327deb882cf99
Enter wordlist file path: wordlist.txt
Wordlist file not found.

==== Python Penetration Testing Toolkit ====

1. Port Scanner
2. Hash Cracker (Dictionary Based)
3. Password Strength Checker
4. File Integrity Checker
5. Subdomain Scanner
6. Exit
Select an option: 3
Enter password: Abc@1234
Strong Password

==== Python Penetration Testing Toolkit ====

1. Port Scanner
2. Hash Cracker (Dictionary Based)
3. Password Strength Checker
4. File Integrity Checker
5. Subdomain Scanner
6. Exit
Select an option: 4
Enter file path: sampl.txt
File not found.

==== Python Penetration Testing Toolkit ====

1. Port Scanner
2. Hash Cracker (Dictionary Based)
3. Password Strength Checker
4. File Integrity Checker
5. Subdomain Scanner
6. Exit
Select an option: 5
Enter domain (example.com): google.com

Scanning subdomains...

Found: www.google.com -> 142.251.150.119
Found: mail.google.com -> 142.251.221.165
