# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection.
The id parameter is unsanitized and can be bypassed on the salesperson page.

Vulnerability #2: Session Hijacking/Fixation.
A new session id is not generated to log back in. The session id that is generated at first loggin in reused. 


## Green

Vulnerability #1: User enumeration.
Unbolded error message is displayed if the user does not exist; That gives information of possible username in the database.

Vulnerability #2: Stored Cross-Site Scrypting.
The input fields for "name" and "feedback" are unsanitized. Unautorized users can send malicious messages with embedded scripts.


## Red

Vulnerability #1: Insecure Direct Object Reference.
Hidden salesperson id are accessible.

Vulnerability #2: __________________
