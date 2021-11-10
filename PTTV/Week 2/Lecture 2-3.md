# Reporting

* Recommendations
* it is a proof of everything that was done
* helps us as a reference for future jobs

* Document all security findings as they happen
* This is where note taking applications are important

## Automated Tool Output

* They only show findings with no analysis or impact to assets
* Do not copy paste from OpenVAS, Nessus or Retina.
* include raw results in an appendix or reference small sections
* We still need to measure risk according to business or customer's mission
* For significant findings, we validate them by exploitation.


## Report Format

* * Executive Summary
  * Introduction
  * Methodology
  * Findings
  * Conclusion
  * Appendixes

* We can find other template formats which may work better for our neccessities.

* Executive Summary
    * A standalone report - Introduction
    * Simple terms
    * explain business risks and business impacts
    * explain in business terms
    * significant findings
    * explain the first few things that must be done
    * summarize the project
    * close with the risks and what has to be done

* Introduction
    * A much more thorough introduction explaining the purpose of the report
    * type of testing
    * why the testing
    * schedules
    * main points of contacts
    * close with risks and some high level findings

* Methodology
    * Describe in detail - process and results of each process
        * Intel
        * Recon
        * Scanning
        * Vulnerability and weakness enumeration
        * Exploitation steps
    * Methodology - similar to the cyber kill chain

    * discuss scope and inventory of all targets with their data
    * list tools and how they were used
    * explain how to recreate the major exploits

    * mainly explaining the methodology if your test doesnt have many findings

* Findings
    * Break down each vulnerability into detailed subsections
    * Steps to recreate it. 
    * The risk it poses to the assets of the company.
    * Try to use screenshots to furthur prove a point, but not in every case
        * dont use raw output from tools as screenshots
        * Edit, highlight or convert to  more appealing format
    * Provide recommendation to mitigate the risk. 
    * patching, changing configuration, fixing software error, include security control( antivirus, firewall, IDS, network filters)
    * Change policy, procedure or process - changing administrative privilages.
    * How to test if fix is successful

* Conclusion
    * no new information
    * summarize project, kind of test, scope, targets
    * risk rating
    * significant findings
    * immediate required actions
    * redundancy is good

* Appendixes
    * long lists, cumbersome results, raw tool outputs(text or xml)
    * source code for exploits
    * screenshots
    * references, diagrams and other useful documents

