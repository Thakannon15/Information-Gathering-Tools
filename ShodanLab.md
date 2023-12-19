# Shodan Information Gathering Lab - Beginner Walkthrough

## Objective:

The objective of this lab is to introduce you to Shodan, a powerful search engine for discovering devices connected to the internet. By the end of this lab, you'll gain hands-on experience in using Shodan to explore devices, services, and vulnerabilities on the internet.

## Prerequisites:

1. **Shodan Account:**
   - Create a Shodan account by visiting [Shodan's website](https://www.shodan.io/). Some features may require a registered account.

## Lab Walkthrough:

### 1. **Search for a Specific IP Address:**

   - Open a terminal and use Shodan to search for information about a specific IP address:
     ```sh
     shodan host <target_ip>
     ```
     Replace `<target_ip>` with the IP address you want to investigate.

### 2. **Explore Shodan Queries:**

   - Learn how to use Shodan queries to filter results. For example, search for devices running a specific service:
     ```sh
     shodan search apache
     ```

### 3. **Identify Devices in a Specific Location:**

   - Use Shodan to identify devices in a specific geographical location. Replace `<city>` and `<country>` with the desired location.
     ```sh
     shodan search city:<city> country:<country>
     ```

### 4. **Search for Vulnerable Devices:**

   - Explore Shodan to find devices with known vulnerabilities. For instance, search for devices vulnerable to Heartbleed:
     ```sh
     shodan search vulnerability:heartbleed
     ```

### 5. **Explore Shodan Filters:**

   - Learn about Shodan filters to narrow down search results. For example, find webcams in a specific city:
     ```sh
     shodan search city:<city> port:554
     ```

### 6. **Investigate Organizations:**

   - Use Shodan to investigate devices associated with a specific organization. Replace `<organization>` with the target organization.
     ```sh
     shodan search org:<organization>
     ```

## Conclusion:

Congratulations! You've completed the Shodan Information Gathering Lab. This beginner-friendly walkthrough should give you a solid foundation in using Shodan for reconnaissance and information gathering.

Feel free to experiment with different queries and filters to enhance your skills. Remember to use this tool responsibly and respect the privacy and security of internet-connected devices.

Happy exploring!
