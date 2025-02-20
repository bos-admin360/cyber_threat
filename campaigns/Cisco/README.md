# Cisco - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cisco or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cisco.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.165.200.7](https://vuldb.com/?ip.5.165.200.7) | 5x165x200x7.dynamic.saratov.ertelecom.ru | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [24.6.144.43](https://vuldb.com/?ip.24.6.144.43) | c-24-6-144-43.hsd1.ca.comcast.net | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [45.32.141.138](https://vuldb.com/?ip.45.32.141.138) | 45.32.141.138.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [45.32.228.189](https://vuldb.com/?ip.45.32.228.189) | 45.32.228.189.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [45.32.228.190](https://vuldb.com/?ip.45.32.228.190) | 45.32.228.190.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [45.55.36.143](https://vuldb.com/?ip.45.55.36.143) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [45.61.136.5](https://vuldb.com/?ip.45.61.136.5) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [45.61.136.83](https://vuldb.com/?ip.45.61.136.83) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [45.61.136.207](https://vuldb.com/?ip.45.61.136.207) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [45.145.67.170](https://vuldb.com/?ip.45.145.67.170) | sirio.rhinorepublic.xyz | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cisco. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-41 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/addemployee.php` | High
2 | File | `/admin/files` | Medium
3 | File | `/controller/Index.php` | High
4 | File | `/etc/init0.d/S80telnetd.sh` | High
5 | File | `/etc/raspap/hostapd/enablelog.sh` | High
6 | File | `/forum/away.php` | High
7 | File | `/goform/aspForm` | High
8 | File | `/index.php` | Medium
9 | File | `/loginVaLidation.php` | High
10 | File | `/mail/index.html` | High
11 | File | `/mgmt/tm/util/bash` | High
12 | File | `/modules/tasks/gantt.php` | High
13 | File | `/mygym/admin/index.php` | High
14 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
15 | File | `/psrs/admin/categories/manage_category.php` | High
16 | File | `/release-x64/otfccdump+0x6b544e` | High
17 | File | `/release-x64/otfccdump+0x6e41a8` | High
18 | File | `/scenegraph/svg_attributes.c` | High
19 | File | `/src/video/x11/SDL_x11yuv.c` | High
20 | File | `/template/wapian/vlist.php` | High
21 | File | `/uncpath/` | Medium
22 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
23 | File | `/wp-admin/admin-ajax.php` | High
24 | File | `admin.color.php` | High
25 | File | `admin.cropcanvas.php` | High
26 | File | `admin.htm` | Medium
27 | File | `admin.php` | Medium
28 | File | `admin.remository.php` | High
29 | File | `admin.webring.docs.php` | High
30 | File | `admin/index.php` | High
31 | File | `admin/index.php?n=databack&c=index&a=dogetsql&tables=<?php` | High
32 | File | `admin/login.php` | High
33 | File | `admincp/auth/checklogin.php` | High
34 | File | `admincp/auth/secure.php` | High
35 | File | `admin_login.asp` | High
36 | File | `advsearch.php` | High
37 | File | `affich.php` | Medium
38 | File | `affiliates.php` | High
39 | File | `akocomments.php` | High
40 | File | `alarm.cc` | Medium
41 | File | `album_portal.php` | High
42 | File | `allopass-error.php` | High
43 | File | `allopass.php` | Medium
44 | File | `al_initialize.php` | High
45 | File | `announce.php` | Medium
46 | File | `apply.cgi` | Medium
47 | ... | ... | ...

There are 410 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2022/08/recent-cyber-attack.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
