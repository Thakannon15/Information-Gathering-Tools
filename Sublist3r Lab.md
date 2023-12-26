# Sublist3r Walkthrough Tutorial

## Introduction:

Welcome to this walkthrough tutorial on using Sublist3r, a tool for enumerating subdomains associated with a target domain. Subdomain enumeration is a crucial step in cybersecurity, helping you discover potential entry points or vulnerabilities in a target's infrastructure.

## Prerequisites:

- A computer with Kali Linux installed.
- Basic familiarity with the Linux command line.

## Lab Setup:

1. **Kali Linux**: Ensure you have Kali Linux installed and updated on your system.

2. **Sublist3r**: Sublist3r is pre-installed on Kali Linux, so you don't need to install it separately. You can confirm its presence by opening a terminal and running `sublist3r -h`.

## Walkthrough Steps:

### Step 1: Launch Kali Linux

1. Start your Kali Linux virtual machine or boot into your Kali Linux system.

### Step 2: Open a Terminal

1. Click on the terminal icon or press `Ctrl + Alt + T` to open a terminal window.

### Step 3: Enumerate Subdomains

1. In the terminal, use Sublist3r to enumerate subdomains for a target domain. Replace `<target_domain>` with the actual domain you want to investigate.
   ```shell
   sublist3r -d <target_domain>
   ```

2. Wait for Sublist3r to complete the enumeration process. It will search various sources for subdomains associated with the target domain.

3. Examine the results that appear in the terminal, which will include discovered subdomains.

### Step 4: Customize Output Format

1. Let's create a more structured output. Rerun Sublist3r with the target domain, but this time, specify the output format as text using the `-o` option. Replace `<output_file>` with the desired output file name.
   ```shell
   sublist3r -d <target_domain> -o <output_file>.txt
   ```

2. Open the output file using a text editor to view the results in an organized format.

### Step 5: Enumerate Subdomains from Multiple Sources

1. You can expand your subdomain enumeration by using multiple sources. Run Sublist3r with the target domain and use the `-b` option to specify additional sources for enumeration.
   ```shell
   sublist3r -d <target_domain> -b google,yahoo
   ```

2. Observe how the choice of sources impacts the number of discovered subdomains.

### Step 6: Investigate Subdomains

1. Select one of the discovered subdomains from the results.

2. Use tools like `nslookup` or `dig` to resolve the IP address associated with the subdomain.
   ```shell
   nslookup <subdomain>
   ```

3. Perform a reverse DNS lookup to identify the host associated with the IP address.
   ```shell
   nslookup <IP_address>
   ```

4. Document your findings and assess the potential security implications.

## Conclusion:

Congratulations! You've completed this Sublist3r walkthrough tutorial. You've learned how to use Sublist3r to enumerate subdomains associated with a target domain, customize output formats, and investigate subdomains. This skill is valuable in cybersecurity and penetration testing. Always remember to use these techniques ethically and responsibly.

Feel free to practice and explore further to enhance your subdomain enumeration skills.

---

This walkthrough tutorial is designed to help beginner college students get started with Sublist3r and subdomain enumeration. You can use it as an educational resource in your coursework or training materials.
