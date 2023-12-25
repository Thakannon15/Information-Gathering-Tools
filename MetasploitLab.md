# Lab: Information Gathering with Metasploit Framework (Kali Linux)

## Objective:

In this lab, you will learn how to use the Metasploit Framework on Kali Linux to gather information about target systems. Metasploit is a versatile tool that can assist in reconnaissance and information gathering during security assessments.

### Prerequisites:

- A Kali Linux system with the Metasploit Framework pre-installed.

# Lab Steps:

## Step 1: Launch Metasploit Console

1. Open a terminal on your Kali Linux system.

2. Type the following command to launch the Metasploit Console:
   ```
   msfconsole
   ```

3. Wait for Metasploit to start. You should see the Metasploit Framework banner.

## Step 2: Search for Modules

1. In the Metasploit Console, you can search for modules related to information gathering. For example, you can search for "port scanners," "reconnaissance," or specific services like "HTTP."

2. Use the `search` command to find relevant modules. For instance:
   ```
   search port scanner
   ```

3. Review the search results and note the module names that you want to use for information gathering.

## Step 3: Load a Module

1. Once you've identified a module, use the `use` command to load it. Replace `[module_name]` with the name of the module you selected. For example:
   ```
   use auxiliary/scanner/portscan/tcp
   ```

2. After loading the module, you can use the `show options` command to view and set any required parameters.

## Step 4: Configure Module Options

1. Set the necessary options for the module. These options may include the target IP address, port range, and other parameters. Use the `set` command to configure the options.

2. For example, if you're using a port scanner module, set the `RHOSTS` option to specify the target IP address or range:
   ```
   set RHOSTS 192.168.1.1-192.168.1.10
   ```

3. Review and ensure that all required options are correctly configured.

## Step 5: Run the Module

1. Once you've configured the module, you can run it using the `exploit` command. This will execute the information gathering process according to the selected module's functionality.

## Step 6: Review and Document Results

1. Examine the results of the information gathering module. You may obtain data such as open ports, service versions, or other valuable information about the target system.

2. Document the gathered information for later analysis or reporting.

### Conclusion:

In this lab, you learned how to use the Metasploit Framework on Kali Linux for information gathering during security assessments. Metasploit offers a wide range of modules that can assist in reconnaissance and data collection. Information gathered during this phase is critical for understanding a target system's vulnerabilities and helps in planning further penetration testing activities. Always ensure that you have proper authorization before conducting any security assessments.
