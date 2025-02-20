# XBash - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _XBash_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XBash:

* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with XBash or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Iron](https://vuldb.com/?actor.iron) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XBash.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [142.44.215.177](https://vuldb.com/?ip.142.44.215.177) | ns554604.ip-142-44-215.net | [Iron](https://vuldb.com/?actor.iron) | High
2 | [144.217.61.147](https://vuldb.com/?ip.144.217.61.147) | ip147.ip-144-217-61.net | [Iron](https://vuldb.com/?actor.iron) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within XBash. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during XBash. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\ASUS\GamingCenterLib` | High
2 | File | `../FILEDIR` | Medium
3 | File | `/account/login` | High
4 | File | `/adherents/note.php?id=1` | High
5 | File | `/admin/ajax.php` | High
6 | File | `/Admin/dashboard.php` | High
7 | File | `/Api/ASF` | Medium
8 | File | `/cgi-bin/cgiServer.exx` | High
9 | File | `/cgi?1&5` | Medium
10 | File | `/clients/editclient.php` | High
11 | File | `/CommunitySSORedirect.jsp` | High
12 | File | `/ctpms/admin/?page=applications/view_application` | High
13 | File | `/dl/dl_sendmail.php` | High
14 | File | `/etc/passwd` | Medium
15 | File | `/formStaticDHCP` | High
16 | File | `/formVirtualApp` | High
17 | File | `/formVirtualServ` | High
18 | File | `/goform/form2WizardStep4` | High
19 | File | `/goform/rlmswitchr_process` | High
20 | File | `/goform/SafeMacFilter` | High
21 | File | `/goform/SafeUrlFilter` | High
22 | File | `/goforms/rlminfo` | High
23 | File | `/include/make.php` | High
24 | File | `/jsonrpc` | Medium
25 | File | `/magnoliaAuthor/.magnolia/` | High
26 | File | `/master/core/PostHandler.php` | High
27 | File | `/medianet/sgcontentset.aspx` | High
28 | File | `/php-sms/classes/Master.php?f=save_quote` | High
29 | File | `/proc/pid/syscall` | High
30 | File | `/restapi/v1/certificates/FFM-SSLInspect` | High
31 | File | `/rrdp` | Low
32 | File | `/settings/profile` | High
33 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-xbash-combines-botnet-ransomware-coinmining-worm-targets-linux-windows/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
