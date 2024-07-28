# CyberArk-REST-API-Bruno
Bruno collections and environments for CyberArk Identity Security REST API testing and automation.

# CyberArk Privilege Cloud REST API
* This collection includes all documented API requests for both Privilege Cloud - Standalone and Shared Services (Identity Security Platform for Shared Services/ISPSS).
* Current up to version 14.2 (July 2024).
* The 'Docs' tab for each request links to the latest version of official API documentation from CyberArk. If you find broken links, please open a pull request.
* The CyberArk Privilege Cloud REST API Environment includes only those environment variables used in either version of Privilege Cloud.

# How to Import
* From the Bruno home page, select 'Import Collection' > 'Bruno Collection' and import the .json file corresponding to your desired API collection.
* Once the collection is imported, a folder is created on the local file system to store the files.
* Inside the Bruno collection's folder on the file system, in the same folder that contains 'bruno.json', create a folder named "environments". Inside the "environments" folder, copy the .bru file corresponding to your desired API environment. You can now assign the environment to specific API requests in your collection.

# Maintained by:
Eli Hopkins (IAM-Jah)
