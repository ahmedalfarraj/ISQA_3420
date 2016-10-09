_________________________________________DFDDictionary___________________________________________
___________________________________________Entites_______________________________________________

The Developer: Person Who is in Charge of the Software Package and License.

The Manager: The Software Package Advisor.

________________________________________End Of Entities__________________________________________

_________________________________________DataStores______________________________________________

NIST Vulnerability DB: The Database that have all the known Vulnerability in the software package.

Software Package License and Vulnerability information DB: Database that keeps Software Package License and Vulnerability information DB

Software Package License and Vulnerability Policy: Database that have Policy Document
_____________________________________End of DataStores__________________________________________

_________________________________________Processes______________________________________________

Retrieve OSS Software Components: Process that will Chick open source software in the document.

Scan for License: A Process of getting information about License for files/Packages

Retrieve List of Software Project License and Vulnerability Information: A Process that will bring Software Project License and Vulnerability Information.

Retrieve Policy for Corresponding Software Project: A Process that will check the information.

Policy Documents Modified: A Process for checking on Policy Document.

_______________________________________End of Processes__________________________________________

__________________________________________Data Flows_____________________________________________

__________________NIST Vulnerability BD TO Retrieve OSS Software Components______________________

OSS Vulnerability Issues: A Process to determine Open Source Issues.

Software Package Name: A Name for the Software Package.
_________________________________________________________________________________________________

___________Retrieve OSS Software Components TO Scan For Licenses And The Developer_______________

Software Package: Codes used to build up the Software.

Software Package and Vulnerability Response:
_________________________________________________________________________________________________

__Retrieve OSS Software Components TO Software Package License and Vulnerability information DB__

Software Package and License And Vulnerability Response:
_________________________________________________________________________________________________

_____The Developer TO Retrieve List of Software Project License and Vulnerability Information____

Project, License and Vulnerability Request: The Developer Request about Package, License and Vulnerability Information.

Project, License and Vulnerability Response: Response to the Developer about Package, License and Vulnerability Information.
_________________________________________________________________________________________________

______________The Developer TO Retrieve Policy for Corresponding Software Project________________

Software Project and Vulnerability Request:

Software Project and Vulnerability Response:
_________________________________________________________________________________________________

Retrieve List of Software Project License and Vulnerability Information TO Software Package License and Vulnerability information DB

Package, License and Vulnerability Request:

Project License and Vulnerability Response:
_________________________________________________________________________________________________

_____The Manager TO Retrieve List of Software Project License and Vulnerability Information______

Project License and Vulnerability Request:

Project, License and Vulnerability Response:
_________________________________________________________________________________________________

__________________________The Manager TO Policy Documents Modified_______________________________

Updated Policy Document: The manager Submit the Document after Checking.

Resent Policy Document: The Document Are Submitted to the Manager for Checking.
_________________________________________________________________________________________________

________Policy Documents Modified TO Software Project  License and Vulnerability Policy__________

Updated Policy Document:

Updated Policy Responded:
_________________________________________________________________________________________________

Retrieve Policy for Corresponding Software Project TO Software Project  License and Vulnerability Policy 

Resent Software Policy Document:

Software Policy Request:
___________________________________________End of Data Flows______________________________________

____________________________________***end of DFDDictionary***____________________________________


















