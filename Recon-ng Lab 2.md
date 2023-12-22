# Social Media Profiling Lab using Recon-ng

## Objective:

In this lab, you will learn how to use Recon-ng to perform Social Media Profiling. Social media profiling involves gathering information from publicly available social media profiles related to a target individual or organization. This exercise will help you understand the importance of securing personal information on social media and the potential risks associated with open profiles.

## Prerequisites:

- A Linux system with Recon-ng installed (Follow the installation guide provided earlier).

## Lab Walkthrough:

### Step 1: Launch Recon-ng

- Open a terminal and launch Recon-ng by running the following command:

   ```shell
   recon-ng
   ```

- You will see the Recon-ng prompt.

### Step 2: Load the Social Media Profiling Module

- Recon-ng provides modules for various tasks. To load the Social Media Profiling module, type the following command:

   ```shell
   use recon/profiles-profiles/social/contacts
   ```

- This module allows you to collect contact information from social media profiles.

### Step 3: Set the Source

- Set the source social media profile URL you want to profile. Replace `<social_media_url>` with the URL of the social media profile you want to investigate:

   ```shell
   set SOURCE <social_media_url>
   ```

   For example:

   ```shell
   set SOURCE https://www.linkedin.com/in/johndoe
   ```

### Step 4: Run the Module

- Execute the module by running:

   ```shell
   run
   ```

- Recon-ng will collect contact information and details from the provided social media profile.

### Step 5: View the Results

- To view the collected contact information and details, type:

   ```shell
   show contacts
   ```

- This will display the information obtained from the social media profile.

### Step 6: Export the Results

- To export the collected information to a file, use the following command:

   ```shell
   db export csv
   ```

- This will create a CSV file with the contact information for further analysis.

### Step 7: Clean Up

- Exit Recon-ng by typing:

   ```shell
   exit
   ```

## Conclusion:

Congratulations! You've successfully completed the Social Media Profiling Lab using Recon-ng. You've learned how to use Recon-ng to gather information from publicly available social media profiles. This knowledge is valuable for understanding the potential risks of sharing personal information on social media and emphasizes the importance of privacy settings.

Remember to always respect privacy and ethical guidelines when conducting social media profiling. This lab provides insights into the information that can be obtained from open profiles, highlighting the need for responsible online behavior.

Feel free to explore other Recon-ng modules and continue practicing your reconnaissance skills. Happy learning!

---

Note: Always ensure that you have proper authorization and follow ethical guidelines when performing any reconnaissance activities. Social media profiling should only be conducted for legitimate and lawful purposes.
