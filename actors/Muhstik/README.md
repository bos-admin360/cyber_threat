# Muhstik - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Muhstik](https://vuldb.com/?actor.muhstik). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.muhstik](https://vuldb.com/?actor.muhstik)

## Campaigns

The following _campaigns_ are known and can be associated with Muhstik:

* CVE-2018-7600 / CVE-2017-10271
* CVE-2019-2725
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Muhstik:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Muhstik.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.116.59.211](https://vuldb.com/?ip.1.116.59.211) | - | - | High
2 | [3.10.224.87](https://vuldb.com/?ip.3.10.224.87) | ec2-3-10-224-87.eu-west-2.compute.amazonaws.com | - | Medium
3 | [5.19.4.15](https://vuldb.com/?ip.5.19.4.15) | relay.zmk.spb.ru | - | High
4 | [18.228.7.109](https://vuldb.com/?ip.18.228.7.109) | ec2-18-228-7-109.sa-east-1.compute.amazonaws.com | Log4Shell | Medium
5 | [34.66.229.152](https://vuldb.com/?ip.34.66.229.152) | 152.229.66.34.bc.googleusercontent.com | - | Medium
6 | [34.221.40.237](https://vuldb.com/?ip.34.221.40.237) | ec2-34-221-40-237.us-west-2.compute.amazonaws.com | - | Medium
7 | [35.160.222.182](https://vuldb.com/?ip.35.160.222.182) | ec2-35-160-222-182.us-west-2.compute.amazonaws.com | - | Medium
8 | [37.187.107.139](https://vuldb.com/?ip.37.187.107.139) | ns326418.ip-37-187-107.eu | - | High
9 | [37.187.253.12](https://vuldb.com/?ip.37.187.253.12) | ns347308.ip-37-187-253.eu | - | High
10 | [45.130.229.168](https://vuldb.com/?ip.45.130.229.168) | - | Log4Shell | High
11 | [46.29.160.149](https://vuldb.com/?ip.46.29.160.149) | - | - | High
12 | [46.218.149.85](https://vuldb.com/?ip.46.218.149.85) | reverse.completel.fr | - | High
13 | [47.135.208.145](https://vuldb.com/?ip.47.135.208.145) | 047-135-208-145.res.spectrum.com | CVE-2018-7600 / CVE-2017-10271 | High
14 | [51.254.219.134](https://vuldb.com/?ip.51.254.219.134) | 134.ip-51-254-219.eu | CVE-2018-7600 / CVE-2017-10271 | High
15 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Muhstik_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Muhstik. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adminlogin.asp` | High
2 | File | `/deviceIP` | Medium
3 | File | `/etc/shadow` | Medium
4 | File | `/firewall/policy/` | High
5 | File | `/getcfg.php` | Medium
6 | File | `/graphStatus/displayServiceStatus.php` | High
7 | File | `/iisadmpwd` | Medium
8 | File | `/index.php/admin/tag/add.html` | High
9 | File | `/Items/*/RemoteImages/Download` | High
10 | File | `/proc/pid/syscall` | High
11 | File | `/rom-0` | Low
12 | File | `/scas/admin/` | Medium
13 | File | `/servlet.gupld` | High
14 | File | `/sql/sql_type.cc` | High
15 | File | `/status` | Low
16 | File | `/tools/developerConsoleOperations.jsp` | High
17 | File | `/uncpath/` | Medium
18 | File | `/usr/bin/pkexec` | High
19 | File | `/WEB-INF/web.xml` | High
20 | File | `ActivityManagerService.java` | High
21 | File | `adm1n/admin_config.php` | High
22 | ... | ... | ...

There are 179 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/68/muhstik-botnet-ioc/
* https://blog.netlab.360.com/botnet-muhstik-is-actively-exploiting-drupal-cve-2018-7600-in-a-worm-style-en/
* https://blog.netlab.360.com/wei-xie-kuai-xun-log4jlou-dong-yi-jing-bei-yong-lai-zu-jian-botnet-zhen-dui-linuxshe-bei/
* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-campaign-briefs/log4j-indicators-of-compromise-to-date/
* https://twitter.com/honeymoon_ioc/status/1474379034926661643
* https://twitter.com/honeymoon_ioc/status/1474379431783317555
* https://twitter.com/honeymoon_ioc/status/1474678995430125568
* https://twitter.com/honeymoon_ioc/status/1474792964736094209
* https://unit42.paloaltonetworks.com/muhstik-botnet-exploits-the-latest-weblogic-vulnerability-for-cryptomining-and-ddos-attacks/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
