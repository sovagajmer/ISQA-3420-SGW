#Data Flow Diagram Dictionary

                                            External Entities
Corporate Developer: Individual corporate developer helps develop code and who provides information (external source code) to which known vulnerabilities are discovered.  

National Vulnerability Database: Checks code to see if there’s any vulnerability that comes along with.

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


CPE Information: Once the CPE information is being stored in National Vulnerability Database datastore then it will send CPE information to Manage NIST/CPE Information.


Package and CPE Information: Contains NIST/CPE Information to store in Risk DB.


Package Information Request: Sends package information request to Risk Database.


Package Information Response: Once the package information being checked then it will send package information response to Manage Project information. 


Project Info Request: Corporate Manager will request Package Information request.


Project Info Response: Once the Package informaiton is risk free then the Manage Package information will send project Info response to Corporate Manger.


Policy Information Request: The Corporate Manager will send the Policy information request to check and see if there is any restriction on the policy regarding open source.


Policy Information Response: Policy Database will send Policy Information Response to Corporate Manager.


Project Information Summary: Once Corporate Manager have everything checked and the file/package is risk free then the project information summary will be sent to the Manage Project Information, similary to the Manifest. 




                                              Data Stores
                                              
NIST CPE Information:This data enables automation of vulnerability management, security measurement, and compliance. NIST also includes databases of security checklists, security related software flaws, misconfigurations, product names, and impact metrics. 


Risk DB: A database which is responisble for identifying, analyzing, evaluating, and controlling risk related with any open source code. 


Policy DB: Policy Database provides a central data source for information on use of External Open source and how to use it. 




