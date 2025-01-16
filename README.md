# IntroToNikto

Overview: In this repository i'll be covering what the nikto tool is, my experience using it, and giving my opinions and thoughts on it.

What is Nikto?
Nikto is a open source tool used for web server scanning to identify potential vulnerabilities and misconfigurations in web servers. It's designed to quickly scan and assess the security posture of web servers by identifying outdated software, insecure configurations, and known configurations. Nikto can be used an alternative for people who don't have access to dirb.

My experience with Nikto: I've been using Nikto for basic http scanning against my target machine, in the attempt to find whatever information was useful such as default files, scripts, and much more. I would usually follow up with all web scanning tools that I know how to use when scanning a target. For example I would run dirb against the target, see what I could get from that and then do a Nikto scan to see if I get any additional information. Since i've only been using Nikto from the offense perspective I have no complaints with this tool, It was said that from a defensive perspective this tool is very noisy without running evasion commands with it triggering Intrussion Detection Systems (IDS).

My thoughts on Nikto: I prefer using Nikto rather than dirb and I honestly can't give a definitive answer on why that is. I feel like I get more information from Nikto. 

Check out my Nikto hands on module when it becomes available.
