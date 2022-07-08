# Application Attacks

## OWASP Top 10
* maintins a list of 10 vulnerabilities web app devs should know about
* Broken Access Control
* Cyrptographic Failure
* Injection Flaw
* Insecure Design
* Security Misconfiguration
* Vulnerable Components
* Authentication Failure
* Integrity Failure
* Monitoring and log Failure
* Request Forgery
* SANS Provides a similar list

## Application Security
* Application Hardening
    * authentication, encryption, validation, known exploits, obfuscation
* Prompt patching is critical

## Prevent SQL Injection

## Cross-Site Scripting
* occurs when an attacker embeds malicious scripts in a thrid-party website that are later run by innocent visitors to that site.
* exmaple: users allowed to use HTMl in their messages

## Request Forgery
* Leverage the fact that users are foften logged into multuiple istes at the same time  and sue one site to trick the browser tinto sending malicious requests to another site without the user's knowledge.
* example: image src GET request

## Directory Traversal
* attacker manipulates the file structure searching for unsecured files

## Overflow Attacks
* Buffer overflow attacks - use input larger than the buffer

## Cookies and attachments
* 

## Session Hijacking
* Guessable Cookies
* Session replay, possible if cookies are not secure and sent over an encrypted connection

## Code Execution Attacks
* when an attacker exploits a vulnerability in a system to that allows them to run commands
* Mitigate these attacks by:
    * Limiting admin access
    * Patch systems and applications

## Privilege escalation
* Seek to take normal accounts and give them admin rights
* mitigation:
    * input validation
    * Patching
    * least privilege principle
    * DEP and ASLR technologies

## Driver manipulation
* Drivers require low-level access to the OS, bridge between OS and hardware
* Refactoring - modifying a driver to carry out malicious activities
* Shimming - wrap legitimate driver with malicious one. Passes requests to legit one like normal but does malicious stuff itself

## Memory Vulnerabilities
* 

## Race conditions
* 