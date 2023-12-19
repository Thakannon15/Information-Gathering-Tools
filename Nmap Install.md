
# Nmap Walkthrough Tutorial for College Students

## Introduction:

Welcome to the Nmap Walkthrough Tutorial for Kali Linux! This tutorial is designed for college students and cybersecurity enthusiasts aiming to learn about Nmap, a powerful network scanning tool. In this guide, we will take you through the process of installing Nmap on your Kali Linux system and showcase its basic usage for network reconnaissance.

## Step 1: Open Terminal

Open the terminal on your Kali Linux system. You can do this by clicking on the terminal icon or using the keyboard shortcut `Ctrl + Alt + T`.

## Step 2: Update Package Lists

Ensure your system has the latest information about available packages by running the following command:

```bash
sudo apt update
```

## Step 3: Install Nmap

Install Nmap using the package manager:

```bash
sudo apt install nmap
```

This will download and install Nmap on your Kali Linux system.

## Step 4: Verify Installation

Verify that Nmap has been successfully installed by checking its version:

```bash
nmap --version
```

This command should display information about the installed Nmap version.

## Basic Nmap Usage:

Now that Nmap is installed, let's explore its basic usage for network scans. Here are a few examples:

### 5.1 Scan a Single Target:

```bash
nmap [target]
```

Replace `[target]` with the IP address or hostname you want to scan.

### 5.2 Scan an Entire Subnet:

```bash
nmap [subnet]
```

Replace `[subnet]` with the subnet you want to scan (e.g., `192.168.1.0/24`).

### 5.3 Save Output to a File:

```bash
nmap -oN output.txt [target]
```

This saves the scan results to a file named `output.txt`.

### 5.4 Aggressive Scan (Enable OS and Version Detection):

```bash
nmap -A [target]
```

This option enables aggressive scanning, including OS and version detection.

### 5.5 Service Version Detection:

```bash
nmap -sV [target]
```

This option attempts to determine service versions running on open ports.

### 5.6 Firewall Evasion Techniques:

```bash
nmap -f [target]
```

Useful for evading firewalls by fragmenting packets.

## Step 6: Example Usage:

Let's put our knowledge into action with some examples:

```bash
# Scan a single target
nmap 192.168.1.1

# Scan an entire subnet
nmap 192.168.1.0/24

# Save output to a file
nmap -oN scan_results.txt 192.168.1.1

# Aggressive scan
nmap -A 192.168.1.1
```

Feel free to explore additional options and customize your scans based on your specific needs. Nmap is a powerful tool for network reconnaissance on your Kali Linux system.

## Conclusion:

Congratulations! You've completed the Nmap Walkthrough Tutorial for Kali Linux. This foundational knowledge of Nmap will serve you well as you explore the world of network scanning and cybersecurity. Experiment with different options and scan scenarios to deepen your understanding of Nmap's capabilities. Happy scanning!
