#Data Flow Diagram Dictionary

                                            External Entities
Corporate Developer: individual corporate developer helps develop code and who provides information (external source code) to which known vulnerabilities are discovered.  

National Vulnerability Database:  checks code to see if there’s any vulnerability that comes along with.

Corporate Manger: The Corporate manager is the person to examine those known vulnerabilities of a software package/project and decides if the project passes known policy.

Manifest: To provide a printable document that can be provided to vendors downstream for a software package/project. In essence, the manifest is a bill of materials that can be shared between organizations in a software supply chain.



                                            Processes
                                            
Manage Submitted File/Package:  This Processes will manage the submitted file 

Manage NIST/CPE Information: This data enables automation of vulnerability management, security measurement, and compliance

Manage Project Information: This processes will manage the package/project information request. 

Manage CPE information (Daily Job):  This processes will manage daily job CPE response and send those response to NIST CPE Information.

Manage Project Information: This process will manage project information once project summary has been submitted by corporate manager. 




                                            Data Flows
File: An individual file within an open-source package.


Package: An open-source grouping of files that a developer submits into the NIST database for review.


Package and CPE Information: Information from the NIST database about the open-source package.


Package Query: The query within the NIST database that searches for information about a particular open-source package.


CPE File: A file regarding information over a partricular open-source package. This is updated daily.


CPE Request: Manage CPE Information will send request to National Vulnerability Database to check and update the information if there any risk along with it. 


CPE Response: Once National Vulnerability Database checks and updates the information, then CPE reponse will give green light to go forward with the open source package. 


CPE Information: This information is 


Package and CPE Information: Contains NIST/CPE Information to store in Risk DB.


Package Information Request: 


Package Information Response:


Project Info Response:


Project Info Request:


Policy Information Request:


Policy Information Response:


Project Information Summary:




                                              Data Stores
NIST CPE Information:


Risk DB:


Policy DB:




