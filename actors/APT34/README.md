# APT34 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT34](https://vuldb.com/?actor.apt34). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt34](https://vuldb.com/?actor.apt34)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT34:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT34.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.19.226.69](https://vuldb.com/?ip.23.19.226.69) | - | - | High
2 | [23.106.215.76](https://vuldb.com/?ip.23.106.215.76) | - | - | High
3 | [23.227.201.6](https://vuldb.com/?ip.23.227.201.6) | 23-227-201-6.static.hvvc.us | - | High
4 | [38.132.124.153](https://vuldb.com/?ip.38.132.124.153) | - | - | High
5 | [45.11.19.47](https://vuldb.com/?ip.45.11.19.47) | - | - | High
6 | [46.4.69.52](https://vuldb.com/?ip.46.4.69.52) | static.52.69.4.46.clients.your-server.de | - | High
7 | [46.105.221.247](https://vuldb.com/?ip.46.105.221.247) | - | - | High
8 | [46.105.251.42](https://vuldb.com/?ip.46.105.251.42) | ip42.ip-46-105-251.eu | - | High
9 | [46.165.246.196](https://vuldb.com/?ip.46.165.246.196) | - | - | High
10 | [70.36.107.34](https://vuldb.com/?ip.70.36.107.34) | - | - | High
11 | [74.91.19.108](https://vuldb.com/?ip.74.91.19.108) | - | - | High
12 | [74.91.19.122](https://vuldb.com/?ip.74.91.19.122) | - | - | High
13 | [80.82.79.221](https://vuldb.com/?ip.80.82.79.221) | - | - | High
14 | [80.82.79.240](https://vuldb.com/?ip.80.82.79.240) | - | - | High
15 | [81.17.56.249](https://vuldb.com/?ip.81.17.56.249) | - | - | High
16 | ... | ... | ... | ...

There are 59 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT34_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT34. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/admin/addemployee.php` | High
3 | File | `/admin/add_trainers.php` | High
4 | File | `/admin/api/theme-edit/` | High
5 | File | `/admin/countrymanagement.php` | High
6 | File | `/admin/generalsettings.php` | High
7 | File | `/admin/newsletter1.php` | High
8 | File | `/admin/payment.php` | High
9 | File | `/admin/subnets/ripe-query.php` | High
10 | File | `/common/info.cgi` | High
11 | File | `/core/conditions/AbstractWrapper.java` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/export` | Low
14 | File | `/file?action=download&file` | High
15 | File | `/filemanager/upload/drop` | High
16 | File | `/hardware` | Medium
17 | File | `/hrm/employeeview.php` | High
18 | File | `/index.php` | Medium
19 | File | `/login.php` | Medium
20 | File | `/mgmt/tm/util/bash` | High
21 | File | `/mkshop/Men/profile.php` | High
22 | File | `/monitoring` | Medium
23 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
24 | File | `/pages/apply_vacancy.php` | High
25 | File | `/php_action/createUser.php` | High
26 | File | `/plugin/LiveChat/getChat.json.php` | High
27 | File | `/plugins/servlet/audit/resource` | High
28 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
29 | File | `/replication` | Medium
30 | File | `/RestAPI` | Medium
31 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/204/apt34-apt-iocs/
* https://github.com/blackorbird/APT_REPORT/tree/master/APT34
* https://unit42.paloaltonetworks.com/unit42-oilrig-group-steps-attacks-new-delivery-documents-new-injector-trojan/
* https://unit42.paloaltonetworks.com/unit42-oilrig-uses-ismdoor-variant-possibly-linked-greenbug-threat-group/
* https://unit42.paloaltonetworks.com/unit42-oilrig-uses-updated-bondupdater-target-middle-eastern-government/
* https://unit42.paloaltonetworks.com/unit42-oopsie-oilrig-uses-threedollars-deliver-new-trojan/
* https://www.clearskysec.com/oilrig/
* https://www.fireeye.com/blog/threat-research/2017/12/targeted-attack-in-middle-east-by-apt34.html
* https://www.fireeye.com/blog/threat-research/2019/07/hard-pass-declining-apt34-invite-to-join-their-professional-network.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
