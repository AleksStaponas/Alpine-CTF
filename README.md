# Alpine-Lab

A lightweight Alpine Linux lab environment designed for penetration testing, vulnerability assessment, and hands-on exploitation practice. Explore common misconfigurations and vulnerabilities involving SSH and WordPress.

## Lab Difficulty

- **Difficulty:** 2/10
- **Platform:** VirtualBox
- **Operating System:** Alpine Linux

## Setup

1. Download the ISO file from the link [alpine-lab.iso](https://mega.nz/file/gioCxTYK#JOLUGyQp8f90Ug6p2h7-aMrRHS0UOY3WWN5nwki3-6Y).
2. Create a new virtual machine in VirtualBox and attach the ISO.

   **Recommended VM Settings:**
   - **RAM:** 2 GB minimum
   - **Storage:** 10 GB minimum

3. Configure the network adapter to use **Bridged Adapter** mode.
4. Boot the machine and log in using the following credentials:
   - **Username:** `root`
   - **Password:** `LazyAdmin111!`
5. Identify the machine's IP address using `ip addr` or discover it with an Nmap scan.

## Objective

Gain access to the machine, and retrieve the flag.

## Hints

<details>
<summary>Hint 1</summary>

Start by identifying the services running on the target. Pay particular attention to the web server and any websites hosted on it.

</details>

<details>
<summary>Hint 2</summary>

The website runs WordPress. Use **WPScan** to enumerate the installation and identify potentially vulnerable components.

</details>

<details>
<summary>Hint 3</summary>

Take a closer look at the plugins installed on the WordPress site. Are any of them outdated or vulnerable?

</details>
