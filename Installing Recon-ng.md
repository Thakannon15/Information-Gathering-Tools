# Installing Recon-ng on Linux

Recon-ng is a powerful open-source tool for information gathering and reconnaissance. To get started with Recon-ng on your Linux system, follow these steps:

**Note:** Recon-ng is primarily designed for Kali Linux and works seamlessly on it. However, you can also install it on other Linux distributions.

1. **Open a Terminal:**
   - Open a terminal window on your Linux system. You'll be using the terminal to execute commands.

2. **Update and Upgrade:**
   - Before installing any new software, it's a good practice to update and upgrade your system's package list. Use the following commands:

   ```shell
   sudo apt update
   sudo apt upgrade
   ```

3. **Install Required Dependencies:**
   - Recon-ng requires certain Python packages and dependencies. Install them using the following command:

   ```shell
   sudo apt install -y python3 python3-pip python3-lxml
   ```

4. **Clone the Recon-ng Repository:**
   - Recon-ng is hosted on GitHub. Clone the repository to your local machine using Git:

   ```shell
   git clone https://github.com/lanmaster53/recon-ng.git
   ```

5. **Navigate to the Recon-ng Directory:**
   - Change your current working directory to the Recon-ng directory:

   ```shell
   cd recon-ng
   ```

6. **Install Additional Dependencies:**
   - Recon-ng requires some additional Python packages. Install them using pip:

   ```shell
   pip3 install -r REQUIREMENTS
   ```

7. **Launch Recon-ng:**
   - You can now start Recon-ng by running the following command:

   ```shell
   ./recon-ng
   ```

   Recon-ng will launch, and you'll be greeted with the Recon-ng prompt.

8. **Optional: Create a Symlink for Easier Access (Recommended):**
   - For easier access, you can create a symlink to the Recon-ng script in a directory that's part of your system's PATH, such as `/usr/local/bin`. This allows you to run Recon-ng from any directory without specifying the full path. Here's how to do it:

   ```shell
   sudo ln -s /path/to/recon-ng/recon-ng /usr/local/bin/recon-ng
   ```

   Replace `/path/to/recon-ng` with the actual path to your Recon-ng installation directory.

9. **Usage and Documentation:**
   - You can now start using Recon-ng for information gathering and reconnaissance. Refer to the official Recon-ng documentation and tutorials for more information on its usage.

   - Official Recon-ng GitHub Repository: [https://github.com/lanmaster53/recon-ng](https://github.com/lanmaster53/recon-ng)

That's it! You've successfully installed Recon-ng on your Linux system. You can start exploring its modules and capabilities for information gathering and cybersecurity reconnaissance.
