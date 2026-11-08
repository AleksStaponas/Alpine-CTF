## Alpine Lab Walkthrough

- Perform an initial Nmap scan to identify open ports and running services.

![[imgs/Step1.png]]

- Manually enumerate the website to identify its structure and available pages.

![[imgs/Step2.png]]

- Run WPScan to enumerate WordPress and identify potential vulnerabilities.

![[imgs/Step3.png]]

![[imgs/Step4.png]]

- Identify a potentially vulnerable WordPress plugin (`wpbookit`).

![[imgs/Step5.png]]

- Test the target to determine whether it is vulnerable to the identified exploit.

![[imgs/Step6.png]]

- Successfully gain access to the web shell.

![[imgs/Step7.png]]

- Enumerate the web shell's directory and list its contents.

![[imgs/Step8.png]]

- Read the contents of `note.txt` to gather additional information.

![[imgs/Step9.png]]

- Attempt a password-spraying attack against the discovered user accounts.

![[imgs/Step10.png]]

- Successfully authenticate via SSH and retrieve the flag.

![[imgs/Step11.png]]