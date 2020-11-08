# the-game-changer

The game changer is a fun and hobby project to collaborate between the builders and breakers. Technically, the secure world does not magically come to existence until you attempt to build one.

**Vision:**

* Gradually, securing all the interconnected devices in the world.
* The aim is to help the breakers (security researchers) and builders (developers) of the world to create code repo for reference. These codes can later be used for automation in various clouds and/or on-premise automation engines.
* An open game to break and build the software and systems of any kind.
* Code should be made available if you have found a better solution at either part.
* Codes in multi-language are welcome. However, should be resided in same CVE or CWE or CAPEC directory.


**Design Description:**

1. There are basically two high-level folders:
* Breakers - to create code snippets for discovering vulnerabilities
* Builders - to create code snippers for mitigating the risks

2. Under each folder there are few main categories:
* Operating System - various types of operating system related vulnerabilities and mitigations
* Network - various types of network related vulnerabilities and mitigations
* Chipset - various types of chipset related vulnerabilities and mitigations
* Protocol - various types of protocol related vulnerabilities and mitigations
* Cloud - various types of cloud related vulnerabilities and mitigations
* Others - any other categories initially will be inserted in to others folder and then re-categoried later

3. Under each main categories there are subcategories. For example, Operating System has following subcategories.
* RHEL - RedHat Enterprise Linux relevant CVE and/or CWE and/or CAPEC exploitations and shields
* Ubuntu - Ubuntu relevant CVE and/or CWE and/or CAPEC exploitations and shields
* Windows - Windows relevant CVE and/or CWE and/or CAPEC exploitations and shields
* Others - Other operating system relevant CVE and/or CWE and/or CAPEC exploitations and shields. It will be re-categoried later when required.

4. Under each subcategories, there are actual fun breaking or building or resolution code snippet. 
For example, under Ubuntu folder, CVE-2002-2086 folder contains five files:
* reference.json - contains the offical link of the original vulnerability.
* For breaker, <CAPEC_ID>-<CWE_ID>-<CVE_ID>.py - the exploitation code to exploit the vulnerability in Python language.
* For breaker, <CAPEC_ID>-<CWE_ID>-<CVE_ID>-test.py - the exploitation code test case to exploit the vulnerability in Python language.
* For builder, <CAPEC_ID>-<CWE_ID>-<CVE_ID>.py - the mitigation code to mitigate the vulnerability in Python language.
* For builder, <CAPEC_ID>-<CWE_ID>-<CVE_ID>-test.py - the mitigation code test case to mitigate the vulnerability in Python language.

5. The exploitation and/or mitigation code snippets can be written in any language as long as we have file extention. Each file should contain these basic following fields:
* Exploitation_Name/Mitigation_Name: <CVE/CWE/CAPEC ID>
* Code Start: "------------------Code_Start-------------------". Rational behind this is to integration with automation it in future.
* Code End: "------------------Code_End-------------------". Rational behind this is to integration with automation it in future.
* Environment Variables should be passed as standard input.
* Code should contain return and pass the test cases.
* Code should be easy to read, modularized in smaller chunks if gets complicated. The rationale behind this is to make is comprehensive even for the newbies.
* Add as more standard comments as possible to help others to understand your mind.
* Codes without test cases should not be submitted. If modification is required on existing codes, it should be reflected to test cases too.
* Any zero day or unknown kernel related vulnerabilities or newly discovered severe vulnerabilities should be consulted with the vendor first before commited to code repo.

**Other Rules:**
* In all, this project is for fun and let's share the fun stuffs as well as leave any specific coporate culture out of it. 
* We are here to help each othe, collaborate with each other and not to make other uncomfortable by pointing fingures to others.
* Criticism are welcome. However, it should be constructive and cooperative as well as human empathy in mind.
* Any offences should be reported and investigated. If its the case, the offender may loose the privilege to contribute temporarily or permanently.

**Milestones:**
* Initial review with the commnunity
* Initial MVP for AWS platform
* Mapping the existing CAPEC-CWE-CVE
* Initial MVP for GCP platform
* Initial MVP for Azure platform
* Extended MVP for AWS on OS, Network, Chipset, Cloud etc.
* Extended MVP for GCP on OS, Network, Chipset, Cloud etc.
* Extended MVP for Azure on OS, Network, Chipset, Cloud etc.
* Engage a wider volunteers to contribute for AWS platform
* Engage a wider volunteers to contribute for GCP platform
* Engage a wider volunteers to contribute for Azure platform


Have fun and bring your best to the game!

![High Level Design Link](https://github.com/tawrid/the-game-changer/blob/main/the-game-changer.png)

**References:**
* CAPEC vs CWE vs CVE:
https://cve.mitre.org/cve_cwe_capec_relationships
* CVE and CWE Correlation:
https://www.cvedetails.com/
* CWE and CAPEC Correlation:
