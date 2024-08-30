<h1 align="center">Bruno Collections for CyberArk Identity Security REST API</h1>

#### CyberArk Self-Hosted REST API:
  This Collection is meant to help self-hosted CyberArk PAM administrators manage and explore the PAM environment with REST API. For ease of use, the Environment JSON file is alphabetized and includes only relevant environment variables. The following services are included:

  * Self-Hosted PAM
  * Central Credential Provider (CCP)
  * Remote Access V2
  * EPM On-Prem

  Current up to Password Vault Web Access (PVWA) v14.2 (Aug 2024) and EPM On-Prem v11.5.6 (Feb 2023/final version).

## Installation

##### To import from JSON (Easiest method):
1. Download the latest version of both the 'Environment' and 'Collection' JSON files that correspond to your environment:
  * Self-Hosted PAM:
    * [Collection](https://github.com/IAM-Jah/CyberArk-REST-API-Bruno/blob/main/CyberArk%20Self-Hosted%20REST%20API/CyberArk%20Self-Hosted%20REST%20API.json)
    * [Environment](https://github.com/IAM-Jah/CyberArk-REST-API-Bruno/blob/main/CyberArk%20Self-Hosted%20REST%20API/Self-Hosted%20Environment.json)

2.  From the Bruno start page, click 'Import Collection' > 'Bruno Collection' and select the Collection JSON file.

> [!IMPORTANT]  
> You must use Bruno v1.19 or later to import JSON files.

3.  Once the Collection is imported, expand the Collection tree down and select any API request. Press 'ctrl'+'e' on the request page to open the Environments menu.

4. Click 'Import' in the lower left then select the Environment JSON file to use with the Collection.

##### To import Bruno Collection natively (Advanced):
1.  Uploading native .bru project files is on the roadmap.

## Roadmap

- [x] Add Privilege Cloud Collections (28 Jul 2024)
- [x] Add Self-Hosted PAM Collection (4 Aug 2024)
- [x] Add Identity and Shared Services to SaaS Collection: (18 Aug 2024)
    - [x] Identity on Shared Services (28 Jul 2024)
    - [x] Dynamic Privileged Access (10 Aug 2024)
    - [x] Connector Management (10 Aug 2024)
    - [x] Remote Access (10 Aug 2024)
    - [x] Endpoint Privilege Manager (For LCD) (10 Aug 2024)
    - [x] Secure Cloud Access (17 Aug 2024)
    - [x] Identity - Workforce Password Management (17 Aug 2024)
    - [x] Identity - SCIM (17 Aug 2024)
    - [x] Secrets Hub (17 Aug 2024)
    - [x] Conjur Cloud (18 Aug 2024)
- [x] Add additional services to Self-Hosted Collection: (30 Aug 2024)
    - [x] Remote Access (30 Aug 2024)
    - [x] Endpoint Privilege Manager (30 Aug 2024)
- [ ] Add usage guide
- [ ] Upload native .bru project files
- [ ] UX enhancements:
    - [ ] Expand documentation
    - [ ] Improve examples for params
    - [ ] Improve examples for bodies
    - [ ] Expand tests and scripts

## Contact

Maintained by Eli Hopkins, [@IAM-Jah](https://github.com/IAM-Jah). Contact information is located in my profile.

## Acknowledgements

This project would not have been possible without the wealth of knowledge made available by Joe Garcia, [@infamousjoeg](https://github.com/infamousjoeg), and others at CyberArk Software.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)