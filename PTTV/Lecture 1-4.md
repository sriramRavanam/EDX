# Methodology

## Types of Penetration Tests

* Network Tests
    * common
    * scans the networks, protocols, hosts and services for vulns and resorces
    * takes a look at perimeter security and/or internal network resources

* Client-Side tests
    * testing the software - custom applications, browsers, configurations, OS
    * client machines

* Web and web application
    * tests the perimeter and functionality of internet-facing web resources
    * code analysis - php - client server model - dbms software, configurations

* Wireless testing
    * auditing use of wireless networks, encryption, authentication, DoS
    * might include iot devices, bluetooth, zigby
    * make sure they use ceritficate based authentication

* Application security test
    * Testing a custom built application for vulns
    * Static code analysis
        * looking at the sourec code to identify flaws, errors, Common Weakness Enumeration ( CWE database)
    * Dynamic analysis test
        * an application runnin in real time
        * or a server that we can interact with to find bugs
        * then we check to see if we can find vulns

* Complete red team test
    * Black box test
    * might try even more social engineering methods

## Testing Methodologies

* Understanding the attacker
    * Cyber kill chain

* Model penetration testing frameworks
    * Penetration testing Framework
    * Penetration Testing Execution Standard
    * Open Source security testing Methodology Manual
    * National INstitute of Standards and Technology 800-115

* Cyber Kill chain - a useful guide
    * https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

    * recon the target
        * DNS cache, network scan
        * learn about the target
    
    * find an exploit for things that may be vulnerable

    * deploying the exploit

    * Exploitation

    * Installing malware - Post Exploitation tools, cover tracks

    * Command and control - maintaining access, tell machine to deliver and launch new exploits

    * Reaching some kind of objective

* Penetration Testing Framework
    * http://www.vulnerabilityassessment.co.uk/Penetration%20Test.html
    * Built like a hierarchy
    * step by step instructions on how we might want to go about the pen test

* Penetration Testing Execution Standard
    * http://www.pentest-standard.org/index.php/Main_Page
    * open source
    * test plan, pre testing interview
    * little outdated

* OSTMM
    * https://www.isecom.org/OSSTMM.3.pdf

* NIST 800 - 115
    * https://www.nist.gov/privacy-framework/nist-sp-800-115

* OWASP Web Testing Guide
    * specific to web applications
    * not for black box
    * written for the organization which owns the software 
    * defines the security measures installed over the life cycle of the application.
    
    * Steps for performing tests 