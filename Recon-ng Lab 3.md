# Real-world Scenario Lab using Recon-ng

## Objective:

In this lab, you will apply your knowledge of Recon-ng in a real-world scenario. You will use Recon-ng to gather information about a simulated target organization. This exercise will provide you with practical experience in reconnaissance and information gathering as it might occur in a real-world cybersecurity assessment.

## Prerequisites:

- A Linux system with Recon-ng installed (Follow the installation guide provided earlier).

## Lab Walkthrough:

### Step 1: Launch Recon-ng

- Open a terminal and launch Recon-ng by running the following command:

   ```shell
   recon-ng
   ```

- You will see the Recon-ng prompt.

### Step 2: Load Modules

- To gather information about the target organization, load appropriate Recon-ng modules. Consider using modules for domain enumeration, email harvesting, and WHOIS lookup based on the information needed.

   - For domain enumeration, you can use a module like `recon/domains-hosts/enumall`.
   - For email harvesting, use the module `recon/domains-hosts/google_site_web`.
   - For WHOIS lookup, use the module `recon/domains-contacts/whois_pocs`.

   Load modules by typing:

   ```shell
   use <module_name>
   ```

   Replace `<module_name>` with the name of the module you intend to use.

### Step 3: Set the Source

- Set the source domain or organization you want to profile. Replace `<target_domain>` with the domain or organization name:

   ```shell
   set SOURCE <target_domain>
   ```

   For example:

   ```shell
   set SOURCE example.com
   ```

### Step 4: Run the Modules

- Execute the loaded modules one by one using the `run` command:

   ```shell
   run
   ```

- Recon-ng will start gathering information based on the selected modules.

### Step 5: View and Analyze Results

- Use commands like `show hosts`, `show domains`, `show emails`, and `show contacts` to view the collected information.

- Analyze the results to understand the target organization's digital footprint, domain names, email addresses, and contact details.

### Step 6: Export and Document

- Export the collected information to a file for documentation and analysis:

   ```shell
   db export csv
   ```

- Create a report summarizing the findings, emphasizing potential security risks, and suggesting mitigation strategies.

### Step 7: Clean Up

- Exit Recon-ng by typing:

   ```shell
   exit
   ```

## Conclusion:

Congratulations! You've successfully completed the Real-world Scenario Lab using Recon-ng. This lab simulated a real-world reconnaissance scenario where you gathered information about a target organization. 

The skills learned in this lab are applicable to real-world cybersecurity assessments and security testing, helping you identify potential vulnerabilities and strengthen security measures.

Remember to always conduct reconnaissance activities ethically, with proper authorization, and within legal boundaries. Responsible information gathering is a crucial aspect of cybersecurity.

Feel free to explore other Recon-ng modules and continue practicing your reconnaissance skills. Happy learning!

---

Note: Always ensure that you have proper authorization and follow ethical guidelines when performing any reconnaissance activities. Reconnaissance should only be conducted for legitimate and lawful purposes.
