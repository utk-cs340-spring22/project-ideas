# World of Code (WOC)
---

### Summary
---

World of Code is a project that has been in development by Dr. Mockus and several undergraduate and graduate researchers. As per their website description, WoC makes it possible to get stratified samples from the entirety of Open Source Software (OSS), measure cross-project code flow and developer/code networks, conduct code or developer census. Additionally, WoC also provides deforking of repositories and aliasing of author IDs. The idea is to help improve a tool that makes research on global properties of OSS possible.


### Project Idea
---

Professor Reid has been working on a functionality tool for WoC. The tool consist in a toolbar where a user is able to enter a vulnerability name. The tool will then pull OSS that has such vulnerability and has yet to be corrected. This application for WoC has been in works and operation for the back-end. WoC is a website that utilizes the Reach framework, so the idea is to set a front end side for the tool in the WoC website and to further develop the application for better functionalites. 

### Problem
---

Many OSS in the web has many vulnerabilities. People that are learning to code tend to pull bits and pieces from several snippets of code they find online. The problem with these portions of code is that they may insert vulnerabilities into the the programmers software. 

### Features
---

The proposed solution would make a front-end portal within WoC which would provide users a search bar. The user will then enter a vulnerability in the search bar. The tool will produce a result file that has the named vulnerability and has not yet been corrected by the author. Additionally, the tool will attempt to pull the history of the file, providing information on other developers that have pulled the file which contains such said vulnerability. This would provide a trace of infected OSS that needs to be reviewed. 

Essentially, this tool will assist coders review their code for vulnerabilities, as well as trace other developers who may be using vulnerable code. 

### Tools Needed
---

The WoC is developed using the Reach framework. The tools that will be used are:
1. React
2. JavaScript
3. HTML
4. CSS

### Who Would Buy/Use this Solution
---
This website and applications will be used by researchers, professors, and students that would like to have their code reviewed by certain vulnerabilities. Additionally, it will provide great amounts of information regarding who is utilizing a particular vulnerable file. 

