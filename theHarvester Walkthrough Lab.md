# theHarvester Information Gathering Lab for Beginners

## Objective:

The objective of this lab is to introduce you to theHarvester, a tool for information gathering. By the end of this lab, you should be comfortable running theHarvester, exploring basic search options, and understanding the gathered information.

### Instructions:

**1. Run theHarvester on a Domain:**
   - Open a terminal on your computer.
   - Navigate to the directory where theHarvester is installed (if you followed the installation guide).
   - Run theHarvester on a domain. Let's use `example.com` as the target domain:
     ```bash
     python3 theHarvester.py -d example.com -b all
     ```
   - Look at the output in the terminal to see what information has been gathered.

**2. Customize Search Options:**
   - Experiment with different search options. Try targeting specific data sources or limiting the results to a particular type of information.
     ```bash
     python3 theHarvester.py -d example.com -b linkedin
     ```
   - Play around with different options to see how it affects the information gathered.

**3. Save Results to a File:**
   - Save the results of your information gathering to a file for future reference.
     ```bash
     python3 theHarvester.py -d example.com -b all -f output.html
     ```
   - Open the generated file (`output.html`) to review and understand the collected information.

**4. Explore Social Media Footprint:**
   - Use theHarvester to focus on social media platforms and gather information related to the target.
     ```bash
     python3 theHarvester.py -d example.com -b all -f output_social.html -s
     ```
   - Open the generated file (`output_social.html`) to see if you can find any social media footprints.

**5. Challenge: Combine Multiple Data Sources:**
   - Run theHarvester with multiple data sources to get a broader set of information.
     ```bash
     python3 theHarvester.py -d example.com -b google,bing,linkedin
     ```
   - Analyze the combined results to see how information varies across different sources.

#### Conclusion:

Congratulations! You've completed theHarvester Information Gathering Lab for Beginners. This hands-on experience should have given you a basic understanding of using theHarvester for information gathering. As you become more comfortable, continue exploring additional options and data sources to enhance your skills.

Feel free to document your findings, ask questions, or share your experience in the repository. Happy investigating!
