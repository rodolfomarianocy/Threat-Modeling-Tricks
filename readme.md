# Threat Modeling
É um processo no qual são detectadas ameaças à segurança durante a fase de Design, podendo mapear e elencar potenciais riscos que podem impactar o fluxo lógico e arquiteturalmente seu négocio. Visando uma estratégia Shift-Left, a introdução do Threat Modeling, facilita a implementação do Security-By-Design para seu S-SDLC.

---

### Dividido em:  
-> Identificação de Ameaças  
-> Identificação dos Perfis de Ameaças  
-> Verificações de Requisitos e Controles de Segurança Implementados  
-> Classificação dos Riscos  

---

## Identificação de Ameaças
É necessário a utilização de um modelo para identificação de ameaças, a mais usada atualmente trata-se da STRIDE, porém também existem outras como: DREAD, VAST, OCTAVE, PASTA, DREAD, TRIKE.  

<a href="https://www.researchgate.net/profile/J-Mcdonald-10/publication/321484000/figure/fig1/AS:597541452263424@1519476392455/STRIDE-threat-model.png"> 
<img height="350em" src="https://developer.ibm.com/developer/default/articles/threat-modeling-microservices-openshift-4/images/STRIDE.png" />
</a>

https://developer.ibm.com/articles/threat-modeling-microservices-openshift-4/  
https://learn.microsoft.com/pt-br/azure/security/develop/threat-modeling-tool-threats  
Para essa fase existem algumas tools que podem ser utilizadas gratuitamente, como a Threat Modeling Tool da Microsoft baseada na metodologia STRIDE:  
https://learn.microsoft.com/pt-br/azure/security/develop/threat-modeling-tool  

## Identificação dos Perfis de Ameaças
É importante Durante o Threat Modeling ter um entedimento claro sobre os Perfis de ameaça, podendo ter entre eles, figuras como:  
-> Fraudador  
-> Spammer  
-> Troll  
-> Ransomware Hacker  
-> Hacktivista  
-> Crime Organizado  
-> Cyber Espionagem(governamental, industrial)  
-> Estelionatário  
-> Hacker  

## Verificações de Requisitos e Controles de Segurança Implementados
Uma vericação de requisitos de segurança pode ser elencada em um threat modeling para ajudar na prevenção de ameaças que foram apontadas inicialmente sendo co-relacionada com o modelo de identificação de ameaças escolhido como por exemplo:  

### ASVS - OWASP Application Security Verification Standard 
O ASVS trata-se de um ótimo framework para isso, pois fornece requisitos para testar os controles técnicos de segurança de aplicações e uma lista de requisitos para desenvolvimento seguro.  
https://owasp.org/www-project-application-security-verification-standard/  

### CIS Critical Security Controls Version 8  
O CIS Critical Security Controls Version 8 também pode ser implementado durante o Threat Modeling, e trata-se de um conjunto de práticas priorizadas recomendadas para a mitigação de ataques cibernéticos.  
https://www.cisecurity.org/controls/v8  

## Classificação dos Riscos
É necessário utilizar uma Metodologias de Classificação de Riscos na elaboração do Threat Modeling, onde servirá como base para priorização dando um ponto focal aos maiores riscos, entre as metodologias mais usadas está:
### OWASP Risk Rating  
<a href="https://www.simplerisk.com/sites/default/files/2021-02/owasp-risk-rating-methodology.png" >
<img src="https://www.simplerisk.com/sites/default/files/2021-02/owasp-risk-rating-methodology.png" />
</a>

https://owasp.org/www-community/OWASP_Risk_Rating_Methodology  

### Implementando Threat Modeling em Pentest
O Threat Modeling é útil na fase de reconhecimento do Pentest, ajudando em ataques mais efetivos que podem ser baseados em frameworks como o CAPEC do MITRE que apresenta uma classificação de padrões de ataques comuns que podem ser usados como guia para exploração.  
https://capec.mitre.org/  
https://threatmodeler.com/threat-modeling-for-security-penetration-testing/  
https://www.triaxiomsecurity.com/threat-modeling-for-penetration-testers/  

### Templates - Microsoft Threat Modeling Tool 
-> AWS Cloud  
https://github.com/EasyAppSecurity/aws-threat-modeling-tool-template  
-> Azure Cloud and Medical Device  
https://github.com/microsoft/threat-modeling-templates  
-> Automotive Threat Modeling  
https://github.com/zhendongma/Automotive_Threat_Modeling  
-> Others  
https://github.com/matthiasrohr/OTMT  

###  Relatório de Threat Modeling de exemplo
Loading... [x]
