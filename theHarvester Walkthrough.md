# Installing theHarvester on Linux

## Objective:

The objective of this guide is to walk you through the installation process of theHarvester on a Linux system. By the end of this process, you should have theHarvester installed and ready to use for information gathering.

### Steps:

**1. Clone theHarvester Repository:**
   - Open a terminal on your Linux system.
   - Clone the theHarvester repository from GitHub using the following command:
     ```bash
     git clone https://github.com/laramies/theHarvester.git
     ```

**2. Navigate to theHarvester Directory:**
   - Move into the theHarvester directory.
     ```bash
     cd theHarvester
     ```

**3. Install Dependencies:**
   - theHarvester requires Python and some additional libraries. Install the required dependencies using the following command:
     ```bash
     sudo apt-get install python3 python3-pip
     ```

**4. Install Required Python Modules:**
   - Install the required Python modules using the following command:
     ```bash
     sudo pip3 install -r requirements.txt
     ```

**5. Run theHarvester:**
   - You can now run theHarvester with the desired options. For example, to perform a Google search, use the following command:
     ```bash
     python3 theHarvester.py -d example.com -b google
     ```

#### Note:

- Adjust the domain and data sources as needed in the command above (`-d example.com` and `-b google`).
- Explore other available data sources by checking the available options using:
  ```bash
  python3 theHarvester.py -h
  ```

#### Additional Information:

- Remember to respect the terms of service of the search engines and platforms you are querying with theHarvester.
- This tool is designed for ethical and legal use for information gathering.

This guide provides a general overview of the installation process. If you encounter any issues or if the steps vary based on your Linux distribution, refer to the official theHarvester documentation or community forums for specific instructions.
