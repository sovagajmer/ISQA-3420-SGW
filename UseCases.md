#Use Cases  

  Text approach (no visio diagrams)
  
 - Title 
  
 - Primary Actor 
 
 - Goal in Context 
 
 - Stakeholders 
 
 - Preconditions 
 
 - Main Success Scenerio 
 
 - Failed End Conditions 
 
 - Trigger
 
Use Case #1  

Title: Developer commits code to be examined for vulnerabilities  

Primary Actor: Developer 

Goal in Context: Gather vulnerability information for all external source code that is used by developers 

Stakeholders: Developer / Manager 

Preconditions: Developer is able to check in external source code to vulnerability system. NIST vulnerability database is up to date.  

Main Success Scenario: Developer checks in code and vulnerability information is recorded to the Risk DB.  

Failed End Conditions: Developer is unable to check in code. Checked in code is not checked for vulnerabilities, failing to update Risk DB.  

Trigger: Code check in  

 
Use Case #2 
  
Title: Manager checks risk database for vulnerabilities/risks
   
Primary Actor: Manager
   
Goal in Context: Check vulnerability information for the external-source code submitted by the Developer.
    
Stakeholders: Manager/Project Owners
 
Preconditions: Developer has submitted files/packages to the NIST database for them to be scanned for vulnerabilities.
 
Main Success Scenario: Manager checkes Risk Database and finds a package contains no vulnerabilities/risks.
 
Failed End Conditions: Manager checks Risk Database and finds a package contains a large number of vulnerabilities/risks.
 
Trigger: Management query 
 
   
Use Case #3 
 
Title: 
   
Primary Actor: 
   
Goal in Context: 
    
Stakeholders: 
 
Preconditions: 
 
Main Success Scenario: 
 
Failed End Conditions: 
 
Trigger: 
