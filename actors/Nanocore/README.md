# Nanocore - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nanocore](https://vuldb.com/?actor.nanocore). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nanocore](https://vuldb.com/?actor.nanocore)

## Campaigns

The following _campaigns_ are known and can be associated with Nanocore:

* Tax-Themed Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nanocore:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nanocore.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.90.16](https://vuldb.com/?ip.2.57.90.16) | - | - | High
2 | [3.18.7.81](https://vuldb.com/?ip.3.18.7.81) | ec2-3-18-7-81.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.220.57.224](https://vuldb.com/?ip.3.220.57.224) | ec2-3-220-57-224.compute-1.amazonaws.com | - | Medium
4 | [3.232.242.170](https://vuldb.com/?ip.3.232.242.170) | ec2-3-232-242-170.compute-1.amazonaws.com | - | Medium
5 | [8.8.8.8](https://vuldb.com/?ip.8.8.8.8) | dns.google | - | High
6 | [20.42.65.92](https://vuldb.com/?ip.20.42.65.92) | - | - | High
7 | [23.221.227.169](https://vuldb.com/?ip.23.221.227.169) | a23-221-227-169.deploy.static.akamaitechnologies.com | - | High
8 | [23.230.152.134](https://vuldb.com/?ip.23.230.152.134) | - | - | High
9 | [23.235.221.158](https://vuldb.com/?ip.23.235.221.158) | vps53141.inmotionhosting.com | Tax-Themed Phishing | High
10 | [31.31.196.51](https://vuldb.com/?ip.31.31.196.51) | server222.hosting.reg.ru | - | High
11 | [34.102.136.180](https://vuldb.com/?ip.34.102.136.180) | 180.136.102.34.bc.googleusercontent.com | - | Medium
12 | [34.117.168.233](https://vuldb.com/?ip.34.117.168.233) | 233.168.117.34.bc.googleusercontent.com | - | Medium
13 | [35.169.217.142](https://vuldb.com/?ip.35.169.217.142) | ec2-35-169-217-142.compute-1.amazonaws.com | - | Medium
14 | [35.205.61.67](https://vuldb.com/?ip.35.205.61.67) | 67.61.205.35.bc.googleusercontent.com | - | Medium
15 | [35.208.225.54](https://vuldb.com/?ip.35.208.225.54) | 54.225.208.35.bc.googleusercontent.com | - | Medium
16 | [37.235.1.174](https://vuldb.com/?ip.37.235.1.174) | resolver1.freedns.zone.powered.by.virtexxa.com | - | High
17 | [37.235.1.177](https://vuldb.com/?ip.37.235.1.177) | resolver2.freedns.zone.powered.by.virtexxa.com | - | High
18 | [38.6.77.91](https://vuldb.com/?ip.38.6.77.91) | - | - | High
19 | [38.48.189.90](https://vuldb.com/?ip.38.48.189.90) | - | - | High
20 | [45.33.6.223](https://vuldb.com/?ip.45.33.6.223) | sqlite.org | - | High
21 | [45.77.55.161](https://vuldb.com/?ip.45.77.55.161) | 45.77.55.161.vultrusercontent.com | - | High
22 | [45.133.174.131](https://vuldb.com/?ip.45.133.174.131) | - | - | High
23 | [50.87.253.125](https://vuldb.com/?ip.50.87.253.125) | box2186.bluehost.com | - | High
24 | [52.20.78.240](https://vuldb.com/?ip.52.20.78.240) | ec2-52-20-78-240.compute-1.amazonaws.com | - | Medium
25 | [52.23.46.39](https://vuldb.com/?ip.52.23.46.39) | ec2-52-23-46-39.compute-1.amazonaws.com | - | Medium
26 | ... | ... | ... | ...

There are 99 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nanocore_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nanocore. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/bin/boa` | Medium
2 | File | `/dev/urandom` | Medium
3 | File | `/etc/quantum/quantum.conf` | High
4 | File | `/exec/` | Low
5 | File | `/getcfg.php` | Medium
6 | File | `/HNAP1` | Low
7 | File | `/mgmt/tm/util/bash` | High
8 | File | `/modules/projects/vw_files.php` | High
9 | File | `/plain` | Low
10 | File | `/staff/tools/custom-fields` | High
11 | File | `/uncpath/` | Medium
12 | File | `/xyhai.php?s=/Auth/editUser` | High
13 | File | `/_next` | Low
14 | File | `actionHandler/ajax_managed_services.php` | High
15 | File | `admin/admin.shtml` | High
16 | File | `ajax-actions.php` | High
17 | ... | ... | ...

There are 137 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0401-0408.html
* https://blog.talosintelligence.com/2022/07/threat-roundup-0715-0722.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0812-0819.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0826-0902.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0909-0916.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0916-0923.html
* https://blog.talosintelligence.com/threat-roundup-0113-0120/
* https://blog.talosintelligence.com/threat-roundup-0120-0127/
* https://blog.talosintelligence.com/threat-roundup-1021-1028-2/
* https://blog.talosintelligence.com/threat-roundup-1028-1104/
* https://blog.talosintelligence.com/threat-roundup-1209-1216/
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-01-12%20Remcos%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-02-15%20Nanocore%20IOCs
* https://isc.sans.edu/forums/diary/Malspam+delivers+NanoCore+RAT/21615/
* https://unit42.paloaltonetworks.com/nanocorerat-behind-an-increase-in-tax-themed-phishing-e-mails/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
