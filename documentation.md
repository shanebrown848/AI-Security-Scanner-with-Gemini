<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build an AI Security Scanner with Gemini

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-security-audit)

**Author:** Shane Brown  
**Email:** shanebrown848@gmail.com

---

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec4e5f6)

---

## Introducing Today's Project!

### Key tools and concepts

Tools I used were Gemini, Also os, dotenv, googles generativeai, and colorama,  Key concepts I learnt include learning that api keys are very important and keep hidden, also utilizing AI with Gemini to complete and help us explain the vulnerabilities and the fixes. The most important skill was learning that a simple color change or scheme helps identify easier.

### Challenges and wins

This project took me approximately an hour and 40 mins, The most challenging part was not focusing on the project, was telling too many stories.  It was most rewarding to realize within that story telling how far I have come since I started learning and building with Nextwork..

### Why I did this project

I did this project today because I wanted to expand and learn how to use AI with security scanning. This project met my goals by teaching me even more, Next, I plan to build off this and implement other scans.

---

## Connecting to Gemini API

In this step, I'm setting up the Gemini API connection. This involves creatinga new project folder and set up your Python environment, also getting your Google AI API key I need to do this so I can setup my .env file with the API key, and then we can test our connection to Gemini.

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec2c3d4)

I verified the connection by running a python script that we created, which we named scanner.py. Gemini responded with Hello, security scanner! which confirmed that our api key is genuine and they in the environment.

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec4e5f6)

My scanner.py file works by we added a section in the code, which it was asking to complete steps which was to validate a common like "admin123", When I ran it, Gemini identified that the code was not strong enough. This shows that the Gemini API can run scripts and libraries like scanning for password strength.

---

## Building the Vulnerability Scanner

In this step, I'm building a vulnerability scanner that will be tested with vulnerable code examples, creating a detailed security prompt for Gemini, and also the test detect of SQL injection.. This will allow me to verify that my scanner tool is properly working.

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec7h8i9)

The vulnerabilities Gemini detected were SQL Injection, Hardcoded Credentials, and Weak Cryptography The security prompt I crafted asked for vulnerability type, and This structured output helps me determine how severe the vulnerability can be or is.

---

## Adding Severity Ratings

In this step, I'm adding severity ratings which are (Critical, High, Medium, Low). I'm also installing colorama to help identify the the severity by color.

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec0k1l2)

I updated the security prompt to include color associated with the severity ratings. The add_colors_to_output function works by Associating what color goes with which rating, When I see CRITICAL in red, it tells me it is sever and needs attention now.

---

## Scanning Real Python Files

In this secret mission, I'm adding a new file which is vulnerable.py.. This lets the scanner scan real Python files, Professional tools do this because it needs to analyze python files before prod.

![Image](http://learn.nextwork.org/encouraged_yellow_silly_yeti/uploads/ai-security-audit_sec3n4o5)

I scanned vulnerable.py by running the scanner.py on vulnerable.py. The vulnerabilities detected were SQL injection,  weak hashing algorithm, and Command injection, The scan_file function works by filepath.

---

## Wrap-up

---

---
