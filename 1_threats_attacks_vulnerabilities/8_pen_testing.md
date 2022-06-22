# **Penetration Testing** 

## Penetration Testing
* Puts security professionals in the role of hackers
* Important to clarify scope of the test, including what is allowed to attack and which methods
    * white box - attacker has knowledge of system
    * grey box - some knowledge
    * black box - no knowledge
* NIST suggests to move back and forth between discovery and attack phases
    * gain access
    * escalate privileges
    * system browsing
    * install additional tools
* Pivoting - after exploiting a vulnerability in a system, use that system as a base to target other systems on the same local network
* Persistence - after exploiting a vulnerability in as system, install tools on that system to allow future access - even if the initial vulnerability is corrected
* Expensive and labor-intensive

## Bug Bounty
* Allows organizations to open their systems to the public inspection
* Harness the work of hackers to harden your system
* Vendors offer self-managed and fully-managed bounty programs

## Exercises
* Some take a competitive format
* Provides hands-on experience attacking
    * Red team - try to undermine security
    * Blue team - Defenders who will secure the systems from attack
    * White team - Observers and judges
    * Purple team - Combines knowledge from the red and blue teams during a lessons-learned session after the exercise
* Capture the flag - red team begins with specific objectives
* Usually done inside a sandbox environment