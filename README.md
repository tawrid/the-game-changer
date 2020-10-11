# the-game-changer

The game changer is a fun and hobby project to collaborate between the builders and breakers. 

**Vision:**

* Gradually, securing all the interconnected devices in the world.
* The aim is to help the breakers (security researchers) and builders (developers) of the world to create code repo for reference.
* An open game to break and build the software and systems of any kind.
* Code should be made available if you have found a better solution at either part.
* Codes in multi-language are welcome. However, should be resided in same CVE or CWE directory.


**Design Description:**

1. There are basically two folders:
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
* RHEL - RedHat Enterprise Linux relevant CVE and/or CWE exploitations and shields
* Ubuntu - Ubuntu relevant CVE and/or CWE exploitations and shields
* Windows - Windows relevant CVE and/or CWE exploitations and shields
* Others - Other operating system relevant CVE and/or CWE exploitations and shields. It will be re-categoried later.

4. Under each subcategories, there are actual fun breaking or building or resolution code snippet. 
For example, under Ubuntu, folder, CVE-2019-19769 folder contains five files:
* reference.txt which contains the offical link of the original vulnerability.
* For breaker, breaker.py, the exploitation code to exploit the vulnerability in Python language.
* For breaker, breaker_test.py, the exploitation code test case to exploit the vulnerability in Python language.
* For builder, builder.py, the mitigation code to mitigate the vulnerability in Python language.
* For builder, builder_test.py, the mitigation code test case to mitigate the vulnerability in Python language.

5. The exploitation and/or mitigation code snippets can be written in any language as long as we have file extention. Each file should contain these following fields:
* Exploitation_Name/Mitigation_Name: <CVE/CWE ID>
* Code Start: "------------------Code_Start-------------------". Rational behind this is to automate it in future.
* Code End: "------------------Code_End-------------------". Rational behind this is to automate it in future.
* Environment Valriables should be passed as standard input.
* Code should contain return and pass the test cases.
* Code should be easy to read, modularized in smaller chunks if gets complicated. The rationale behind this is to make is comprehensive for the newbies.
* Codes without test cases should not be submitted. If modification required, it should be reflected to test cases too.
* Any zero day or unknown kernel related vulnerabilities or unknown severe vulnerabilities should be consulted with the vendor first before commited to code repo.

Other Rules:
* In all, this project is for fun and let's share the fun stuffs as well as leave any specific coporate culture out of it. 
* We are here to help each othe, collaborate with each other and not to make other uncomfortable by pointing fingures to others.
* Criticism are welcome. However, it should be constructive and cooperative.
* Any offences should be reported and investigated. If its the case, the offender may loose the privilege to contribute temporarily or permanently.

Have fun and bring your best to the game!

![High Level Design Link](https://github.com/tawrid/the-game-changer/blob/main/the-game-changer.png)
