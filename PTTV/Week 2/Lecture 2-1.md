# Pen Test process and preparation.

Methodologies

## Preparation
    * Customer interview
    * Define testing scope (targets)
    * Define the rules of engagement
    * Complete liability waiver, NDA, permission memo
    * Create test team and set roles
    
## Testing
    * Perform test, following any methodology
    * finish tests with results and findings

## Conclusion
    * Measure the findings against business assets or concerns and threats
    * Write and present reports of findings and recommendations
    * Re-test if required and then specify findings

* Interview customer - learn about the target. learn about what they want about the test
        What are they most concerned about.

* Customer concerns
* Authorizations
* what does customer want to protect

* We then find what kind of test fits the customer's needs best.
* Then we can define the scope and the targets
* Scope needs to be agreed upon by both customer and tester
* Avoid Scope creep - make sure to ask what exactly is in scope and what is out.

* make sure you have authorization from the companies to test the software they _own_

* we want to know 
    * who owns the cloud
    * is it shared by other tenants
    * Would we need explicit permission - mostly yes
    * We can only test what customer owns not third party networks

* What are we targeting
    * we dont want to target the production environment
    * we should target the test environment, since we dont want to impact their production
    * but the production network is the one that adversaries will targer, hence ideally, we must target this.
    
* We must agree to terms in the ROE (rules of engagement) which may define - 
    * Test times
    * kinds of tests
    * points of contacts
    * briefings
    * problem solving
    * Dealing with sensitive data and avoiding unnecessary disclosures

* ROE - Important if we are doing a red team test. 

* SoW - Statement of Work. 
    * price
    * dates for deliverables
    * briefing requirements
    * list all applicable documents
    * list main Points of Contacts representing both customer and testing team

## Penetration Test Plan

* includes all the previous documents
* steps for the technical tests we perform
* So we prep a plan.
* this also keeps the organization informed about our activities and schedule.