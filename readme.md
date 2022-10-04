# Threat Modeling

It is a process in which security threats are detected, and potential risks that can impact the logical flow and architecture of systems can be mapped and listed. Aiming at a Shift-Left strategy, the introduction of Threat Modeling facilitates the implementation of Security-By-Design for your S-SDLC in the Design phase.

---
### Divided in:
-> Threat Identification  
-> Identification of Threat Profiles  
-> Verification of Implemented Security Requirements and Controls  
-> Risk Classification  

---

## Threat Identification
It is necessary to use a model to identify threats, the most used currently is STRIDE, but there are also others such as: DREAD, VAST, OCTAVE, FOLDER, DREAD, TRIKE.

<a href="https://www.researchgate.net/profile/J-Mcdonald-10/publication/321484000/figure/fig1/AS:597541452263424@1519476392455/STRIDE-threat-model.png"> 
<img height="350em" src="https://developer.ibm.com/developer/default/articles/threat-modeling-microservices-openshift-4/images/STRIDE.png" />
</a>

https://developer.ibm.com/articles/threat-modeling-microservices-openshift-4/  
https://learn.microsoft.com/pt-br/azure/security/develop/threat-modeling-tool-threats  
For this phase there are some tools that can be used for free, 
such as Microsoft's Threat Modeling Tool based on the STRIDE methodology:
https://learn.microsoft.com/pt-br/azure/security/develop/threat-modeling-tool  

e.g.  

<img height=350em src="https://user-images.githubusercontent.com/54555784/193932981-65206db9-0c47-415a-a668-ac9ef8dfb287.png" />

## Identification of Threat Profiles
It is important during Threat Modeling to have a clear understanding of the threat profiles, that is, the profiles of attackers that can exploit certain threats, which may include figures such as:
-> fraudster  
-> Spammer  
-> Troll  
-> Ransomware Hacker  
-> hacktivist  
-> Organized Crime  
-> Cyber Espionage (governmental, industrial)  
-> Cyber terrorism  
-> Hacker  
etc...

## Requirements Checks and Implemented Security Controls
A security requirements check can be listed in a threat modeling to help prevent threats that were initially identified and correlated with the chosen threat identification model, for example:

### ASVS - OWASP Application Security Verification Standard 
ASVS is a great framework for this, as it provides requirements for testing technical application security controls and a list of requirements for secure development.  
https://owasp.org/www-project-application-security-verification-standard/  

### CIS Critical Security Controls Version 8  
CIS Critical Security Controls Version 8 can also be implemented during Threat Modeling, and is a set of prioritized best practices for mitigating cyber attacks.  
https://www.cisecurity.org/controls/v8  

## Risk Classification
It is necessary to use a Risk Classification Methodologies in the elaboration of Threat Modeling, which will serve as a basis for prioritization, giving a focal point to the greatest risks, among the most used methodologies are:

### OWASP Risk Rating  
<a href="https://www.simplerisk.com/sites/default/files/2021-02/owasp-risk-rating-methodology.png" >
<img src="https://www.simplerisk.com/sites/default/files/2021-02/owasp-risk-rating-methodology.png" />
</a>

https://owasp.org/www-community/OWASP_Risk_Rating_Methodology  

### Implementando Threat Modeling em Pentest
The Pentest with Threat Modeling approach aims to implement a more comprehensive threat analysis strategy adding greater executive value by defining specific risks for the business, and also adds value to Pentest execution, since with more information provided about the application architecture, the pentest will be performed with better efficiency.

#### Threat Modeling approach - TEMPLATE
https://github.com/rodolfomarianocy/Threat-Modeling-Tricks/blob/main/report_template.docx  

-> References:  
https://threatmodeler.com/threat-modeling-for-security-penetration-testing/  
https://www.triaxiomsecurity.com/threat-modeling-for-penetration-testers/  

### Templates - Microsoft Threat Modeling Tool 
-> AWS Cloud  
https://github.com/EasyAppSecurity/aws-threat-modeling-tool-template  
-> Azure Cloud and Medical Device  
https://github.com/microsoft/threat-modeling-templates  
-> Automotive Threat Modeling  
https://github.com/zhendongma/Automotive_Threat_Modeling  
-> Other  
https://github.com/matthiasrohr/OTMT  
