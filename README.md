# Project Overview
A small e-commerce company stores information on a remote database server, since many of the employees work remotely from locations all around the world. The database has been open to the public since the company's launch, but keeping the database server open to the public is a serious vulnerability. I was tasked with performing a vulnerability assessment of the situation to communicate the potential risks to decision makers at the company. I created a written report that explains how the vulnerable server is a risk to business operations and how it can be secured.


I included the following in my report:
- __A system description__  in which I highlighted the relevant components, architecture, and dependencies of the system being assessed.
- __Scope of the Assessment__ in which I specified the focus and boundaries of the assessment.
- __Purpose of the Assessment__  in which I explained the stakeholders underlying objective and intended outcome of the analysis.
- __Risk Assessment__ :
                         - I Choose the threats based on the information gathered from the system description, scope, purpose, and NIST SP 800-30 Rev. 1 resource.
                         - Using the Threat events section in the NIST SP 800-30 Rev. 1 resource. I identified threat events that could be initiated based on the threats identified.
                         - I referred to the likelihood and severity sections of the NIST SP 800-30 Rev. 1 resource, I estimated a Likelihood score (1-3) and Severity score (1-3) for each threat
                           and then calculated an overall Risk score (1-9) for each threat using the formula (likelihood x severity = risk). 

- __Approach__ in which I tried to explain to the stakeholders understand my thought process of evaluating the risks I identified — adding valuable context for stakeholders.
- __Remediation strategy__ in which I summarized specific security controls that could be implemented to remediate or mitigate the risks to the information system.


### Summary
The server runs on the latest version of Linux operating system and hosts a MySQL database management system.The scope of this vulnerability assessment relates to the current access controls of the system. The database server is of  high value and as well as exposed to  high risk with the most risk presented by hackers having a risk score of 9. It must be protected in order to keep the business running. Implementation of authentication, authorization, and auditing mechanisms must be ensure so that only authorized users access the database server along with encryption of data in motion should be done using TLS instead of SSL.

---


 










# Analyzing-a-vulnerable-system
I conducted a vulnerability assessment for a small e-commerce company. 
