# Risk Scoring Methodologies

* Risk 
    * a vulnerability assessment
    * analytical assesment and help prioritize the findings for the customer
    * assess and score everything we find

* CVSS - Common Vulnerability Scoring System
    * risk is based on vulnerability
    * scores vulnerabilities from 1-10
    * higher the score, more the vulnerability is a potential point of failure.
    * open industry standard, now on revision 3.1
    * falls short of assessing what the impact of a vulnerability is.
    * broken down into parts.
        * Base score - Raw impact score for the vulnerability - Exploitability and Impact - All scored as none, low or high.
            * Exploitability -> Attack Vector, Attack complexity, Privileges required, User Interaction.
            * Impact -> Confidentiality impact , Integrity impact, Availability impact, User Interaction.

        * Temporal Metric Group
            * Exploit code maturity
            * remediatoin level
            * report confidence
        
        * Environmental metric group
            * confidentiality requirement
            * integrity requirement
            * availability requirement
            * modified base metrics
    
* NIST - National Institute of Standards and Technology
    * 800 - 30 : Guide for Conductiong Risk Assessment

    * Identifies threat sources and threat events, And then assesses the risk of the information loss if the threat event occurs.

    * Impact of the threat event
    * Liklihood of Initiation
    * Liklihood of Adverse Impact
    
    * Risk = Impact + Likelihoods of ( Initiation + Adverse Impact )
    * helps provide recommendations in a test report.
    * often expressed as negligible, low, moderate, high, critical.

* Selecting a methodology dependst on the target and test type.
* which would be most useful to customer.
* CVSS is great but it isnt enough, We need to assess risk for each instance of a vuln.
    