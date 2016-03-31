#Use Cases
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
 
Preconditions:   

-Developer has submitted files/packages to the NIST database for them to be scanned for vulnerabilities. 
-Vulnerabilities have been submitted to the risk database.
 
Main Success Scenario: Manager checkes risk database and finds a package contains no vulnerabilities/risks.
 
Failed End Conditions: Manager checks risk database and finds a package contains a large number of vulnerabilities/risks.
 
Trigger: Management query 
 
   
                                                    Use Case #3 
 
Title: Produce Manifest
    
Primary Actor: Corporate Manager
   
Goal in Context: The goal of the context is to create and send a project information summary to be produced into a manifest.
    
Stakeholders: Corporate Managers/Project Managers/Future Developers
 
Preconditions: Open-source packages need to have been approved by the rules within the Policy document. Information about the project is then stored in the manifest.
 
Main Success Scenario: A Manifest is created which will help the project continue to progress in the future. It is helpful for organizational purposes and will help the project move towards completion.
 
Failed End Conditions: A proper manifest is not created and the project struggled to progress.
 
Trigger: Open-source packages are approved by the Policy standards.
