# Codepath_Unit9
# Project 8 - Pentesting Live Targets

Time spent: **5** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQLI in blue link

Description:
When I tried to put 'OR 1=1' to the id secssion on find Contact it said the database inquirey failed which came from the sql.

![SQLinjection](https://user-images.githubusercontent.com/32893841/142968641-bc4fd905-37bd-4798-9385-d4aa99f80d05.gif)



## Green

Vulnerability #1: XSS attack on green link

Description:
When I put javascript inside contact box the feedback secssion xecutes the code. 
![XssAttack](https://user-images.githubusercontent.com/32893841/142968915-07efb6e4-1dcc-48d1-9436-b0acb3365263.gif)




## Red

Vulnerability #2: IDOR in red Link

Description:
When I changed id values directly from the url it refrences to another user. 
![IDOR attack](https://user-images.githubusercontent.com/32893841/142968740-df346802-0c7c-4d31-8fcb-2ea51a705bc1.gif)




## Notes

Describe any challenges encountered while doing the work
