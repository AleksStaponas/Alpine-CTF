# Alpine Lab Walkthrough

- Perform an initial Nmap scan to identify open ports and running services.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step1.png" alt="Nmap scan">
</p>

- Manually enumerate the website to identify its structure and available pages.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step2.png" alt="Website enumeration">
</p>

- Run WPScan to enumerate WordPress and identify potential vulnerabilities.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step3.png" alt="WPScan results" width="600">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step4.png" alt="WPScan enumeration">
</p>

- Identify a potentially vulnerable WordPress plugin (`wpbookit`).

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step5.png" alt="Vulnerable plugin discovery">
</p>

- Test the target to determine whether it is vulnerable to the identified exploit.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step6.png" alt="Exploit testing">
</p>

- Successfully gain access to the web shell.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step7.png" alt="Web shell access">
</p>

- Enumerate the web shell's directory and list its contents.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step8.png" alt="Directory enumeration">
</p>

- Read the contents of `note.txt` to gather additional information.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step9.png" alt="Reading note.txt">
</p>

- Attempt a password-spraying attack against the discovered user accounts.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step10.png" alt="Password spraying">
</p>

- Successfully authenticate via SSH and retrieve the flag.

<p align="center">
  <img src="https://raw.githubusercontent.com/AleksStaponas/Alpine-CTF/main/imgs/Step11.png" alt="SSH access and flag retrieval">
</p>
