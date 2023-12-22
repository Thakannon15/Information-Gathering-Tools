# Email Harvesting Lab using Recon-ng on Kali Linux

## Objective:

In this lab, you will learn how to use Recon-ng on Kali Linux to perform Email Harvesting. Email harvesting is the process of collecting email addresses associated with a target domain. This exercise will help you understand how attackers can gather email addresses, and it emphasizes the importance of protecting such information.

## Prerequisites:

- A Kali Linux system with Recon-ng installed (Follow the installation guide provided earlier).

## Lab Walkthrough:

### Step 1: Launch Kali Linux Terminal

- Open a terminal window on your Kali Linux system. You will use the terminal to run Recon-ng commands.

### Step 2: Launch Recon-ng

- To launch Recon-ng, simply enter the following command in the terminal:

   ```shell
   recon-ng
   ```

- You will now see the Recon-ng prompt.

### Step 3: Load the Email Harvesting Module

- Recon-ng provides modules for various tasks. To load the Email Harvesting module, type the following command:

   ```shell
   use recon/domains-hosts/google_site_web
   ```

- This module allows you to search Google for websites related to a domain.

### Step 4: Set the Source

- Set the source domain you want to harvest emails from. Replace `<target_domain>` with the domain of your choice:

   ```shell
   set SOURCE <target_domain>
   ```

   For example:

   ```shell
   set SOURCE example.com
   ```

### Step 5: Run the Module

- Execute the module by running:

   ```shell
   run
   ```

- Recon-ng will query Google and retrieve a list of websites related to the target domain.

### Step 6: View the Results

- To view the harvested email addresses, type:

   ```shell
   show hosts
   ```

- This will display a list of websites along with any email addresses found on those websites.

### Step 7: Export the Results

- To export the harvested email addresses to a file, use the following command:

   ```shell
   db export csv
   ```

- This will create a CSV file with the email addresses for further analysis.

### Step 8: Clean Up

- Exit Recon-ng by typing:

   ```shell
   exit
   ```

## Conclusion:

Congratulations! You've successfully completed the Email Harvesting Lab using Recon-ng on Kali Linux. You've learned how to use Recon-ng to gather email addresses associated with a target domain. Remember that email harvesting should always be done ethically and responsibly, respecting privacy and applicable laws.

Email harvesting is not only used by cybersecurity professionals but also by attackers. Understanding these techniques is essential for protecting sensitive information and enhancing security measures.

Feel free to explore other Recon-ng modules and continue practicing your reconnaissance skills. Happy learning!

---

Note: Always ensure that you have proper authorization and follow ethical guidelines when performing any reconnaissance activities. Email harvesting should only be conducted for legitimate and lawful purposes.
