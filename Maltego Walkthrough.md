# Installing Maltego on Linux

## Objective:

The objective of this guide is to walk you through the installation process of Maltego on a Linux system. By the end of this process, you should have Maltego installed and ready to use for information gathering.

### Prerequisites:

1. **Maltego Account:**
   - Ensure that you have a Maltego account. You can register for one on the [official Maltego website](https://www.maltego.com/).

#### Steps:

**1. Download Maltego:**
   - Visit the [Maltego download page](https://www.maltego.com/download/) on the official website.

**2. Choose the Version:**
   - Select the appropriate version of Maltego based on your use case. There are different editions available, including Maltego CE (Community Edition) and commercial editions.

**3. Download Maltego:**
   - Click on the download link for the chosen version. This will download the Maltego installation package to your system.

**4. Extract the Archive:**
   - Open a terminal and navigate to the directory where the Maltego archive was downloaded.
     ```bash
     cd /path/to/downloaded/file
     ```
   - Extract the archive using a command similar to the following (replace `maltego-version-linux-community.zip` with the actual file name):
     ```bash
     unzip maltego-version-linux-community.zip
     ```

**5. Navigate to the Maltego Directory:**
   - Move into the extracted Maltego directory.
     ```bash
     cd maltego-version-linux-community
     ```

**6. Run Maltego:**
   - Run the Maltego executable to launch the application.
     ```bash
     ./maltego
     ```
   - If you encounter permission issues, you may need to give execute permissions to the Maltego executable:
     ```bash
     chmod +x maltego
     ```

**7. Sign In:**
   - Sign in to Maltego using your Maltego account credentials.

**8. Explore Maltego:**
   - Once signed in, you can start exploring Maltego and using it for information gathering.

#### Note:

- For commercial editions, you might need to follow additional steps and provide license information during the installation process.
- Ensure that your system meets the minimum requirements specified on the Maltego website.

This guide provides a general overview of the installation process. If you encounter any issues or if the steps vary based on your Linux distribution, refer to the official Maltego documentation or community forums for specific instructions.
