<h1 align="center">Bruno Collections for CyberArk Identity Security REST API</h1>

#### CyberArk Privilege Cloud and Shared Services REST API:
  This Collection is meant to help CyberArk Privilege Cloud and CyberArk Identity administrators manage and explore the CyberArk Shared Services/SaaS environment with REST API. For ease of use, the Environment JSON file is alphabetized and includes only relevant environment variables. All default services that are part of the Shared Services platform are included:

  * CyberArk Privilege Cloud - Standard
  * CyberArk Privilege Cloud - Shared Services
  * CyberArk Identity - Shared Services
  * Connector Management
  * Secure Infrastructure Access (SIA)
  * Secure Cloud Access (SCA)
  * Remote Access V2
  * EPM SaaS (for EPM LCD)
  * Secrets Hub
  * Central Credential Provider (CCP)
  * Conjur Cloud

  Current up to Privilege Cloud v14.7 (August 2025)

## Installation

##### To import:
1.  Install [Bruno](https://www.usebruno.com/downloads) (if not already installed).

2.  **Clone** this repository locally:
    ```bash
    git clone https://github.com/IAM-Jah/CyberArk-REST-API-Bruno/
    ```
2.  From the Bruno start page, click 'Open Collection'.

3.  Browse to the cloned repository's root folder and select it.
    This will load the .bru collection in Bruno.

4.  Confirm you have loaded the collection "Privilege Cloud and Shared Services REST API v1.2" and the environment "ISPSS Environment" before making requests.

## Roadmap

- [x] Add Privilege Cloud Collections (28 Jul 2024)
- [x] Add Self-Hosted PAM Collection (4 Aug 2024)
- [x] Add Identity and Shared Services to SaaS Collection: (18 Aug 2024)
    - [x] Identity on Shared Services (28 Jul 2024)
    - [x] Secure Infrastructure Access (10 Aug 2024)
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
- [x] Add usage guide (14 Oct 2024)
- [x] Upload native .bru project files (7 Aug 2025)
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