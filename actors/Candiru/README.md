# Candiru - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Candiru](https://vuldb.com/?actor.candiru). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.candiru](https://vuldb.com/?actor.candiru)

## Campaigns

The following _campaigns_ are known and can be associated with Candiru:

* CatalanGate

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Candiru:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Candiru.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.67.82](https://vuldb.com/?ip.5.2.67.82) | xanthium.astrotrain.xyz | - | High
2 | [5.2.75.217](https://vuldb.com/?ip.5.2.75.217) | mq.is | - | High
3 | [5.206.224.54](https://vuldb.com/?ip.5.206.224.54) | - | - | High
4 | [5.206.224.197](https://vuldb.com/?ip.5.206.224.197) | - | - | High
5 | [5.206.224.226](https://vuldb.com/?ip.5.206.224.226) | gofast | - | High
6 | [5.206.227.93](https://vuldb.com/?ip.5.206.227.93) | noos-proxy | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Candiru_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 25 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Candiru. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `/.dbus-keyrings` | High
3 | File | `/acms/classes/Master.php?f=delete_cargo` | High
4 | File | `/addnews.html` | High
5 | File | `/addsrv` | Low
6 | File | `/admin.php/news/admin/topic/save` | High
7 | File | `/admin/addemployee.php` | High
8 | File | `/admin/comn/service/update.json` | High
9 | File | `/Admin/Views/FileEditor/` | High
10 | File | `/api/user/{ID}` | High
11 | File | `/article/add` | Medium
12 | File | `/asms/classes/Master.php?f=delete_transaction` | High
13 | File | `/auth/register` | High
14 | File | `/cgi-bin/uploadWeiXinPic` | High
15 | File | `/controller/pay.class.php` | High
16 | File | `/ctpms/admin/?page=applications/view_application` | High
17 | File | `/dev/block/mmcblk0rpmb` | High
18 | File | `/dev/kmem` | Medium
19 | File | `/dev/snd/seq` | Medium
20 | File | `/device/device=140/tab=wifi/view` | High
21 | File | `/dl/dl_print.php` | High
22 | File | `/etc/passwd` | Medium
23 | File | `/getcfg.php` | Medium
24 | File | `/goform/SetClientState` | High
25 | File | `/goform/SysToolChangePwd` | High
26 | File | `/irj/servlet/prt/portal/prtroot/com.sap.portal.usermanagement.admin.UserMapping` | High
27 | File | `/jerry-core/ecma/base/ecma-gc.c` | High
28 | File | `/jerry-core/ecma/base/ecma-helpers-conversion.c` | High
29 | File | `/librarian/bookdetails.php` | High
30 | File | `/librarian/lab.php` | High
31 | File | `/login` | Low
32 | File | `/mngset/authset` | High
33 | ... | ... | ...

There are 285 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://citizenlab.ca/2022/04/catalangate-extensive-mercenary-spyware-operation-against-catalans-using-pegasus-candiru/
* https://github.com/eset/malware-ioc/tree/master/swc-candiru

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
