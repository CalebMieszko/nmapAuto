# nmapAuto | credit to Thiago Pires (https://medium.com/@thiagopires_33005)
This app requires you to use a Linux distribution. 

If you're watching my presentation, we'll be using Kali Linux since it comes pre-packaged with a ton of common and useful cybersecurity tools and is beginner-friendly. For advanced Linux users, my most-recommended Linux distribution is Arch if you feel comfortable manually installing all of your apps and tools. 

1. Open a terminal in the 'app' folder 
 - You can do this with a command like 'cd app' if you're in the nmapauto folder instead
 - You can tell where you are by running pwd
    - That stands for path within directory and will show you in the terminal which folder you're in
2. Run "sudo bash requirements.sh"
3. Run "sudo ./runNmap.sh"
4. Thats it!

HOW IT WORKS

Automated Subnet Scanning: The script starts by identifying your subnet and finding live hosts.

Scan Options: After identifying live hosts, the script offers four types of scans: Complete, Fast, Stealthy, and Vulnerability-focused.

It will identify your device's Ip and exclude it from the scan

Dynamic Rate Limiting: Customizable rate limiting based on the target's sensitivity.

Structured Output: All scan results are saved in subdirectories, organized by date and time, including XML files for further analysis.

Audit Logging: An audit log is generated for accountability, tracking who initiated the scan and when.

Video: https://www.youtube.com/watch?v=ycRVXsn7IC8&feature=youtu.be