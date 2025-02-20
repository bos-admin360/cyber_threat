# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\totalcmd\TOTALCMD64.EXE` | High
2 | File | `//proc/kcore` | Medium
3 | File | `//WEB-INF` | Medium
4 | File | `/acms/admin/?page=transactions/manage_transaction` | High
5 | File | `/admin/` | Low
6 | File | `/admin/api/theme-edit/` | High
7 | File | `/admin/del.php` | High
8 | File | `/admin/folderrollpicture/list` | High
9 | File | `/Admin/login.php` | High
10 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
11 | File | `/admin/usermanagement.php` | High
12 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
13 | File | `/bin/httpd` | Medium
14 | File | `/blog/edit` | Medium
15 | File | `/car-rental-management-system/admin/manage_user.php` | High
16 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
17 | File | `/cgi-bin/login.cgi` | High
18 | File | `/company/down_resume/total/nature` | High
19 | File | `/ctpms/admin/?page=applications/view_application` | High
20 | File | `/exponent_constants.php` | High
21 | File | `/forum/away.php` | High
22 | File | `/goform/SystemCommand` | High
23 | File | `/goform/WifiBasicSet` | High
24 | File | `/hospital/hms/admin/patient-search.php` | High
25 | File | `/hrm/index.php?msg` | High
26 | File | `/hrm/state.php` | High
27 | File | `/include/chart_generator.php` | High
28 | File | `/index.php` | Medium
29 | File | `/index/user/user_edit.html` | High
30 | File | `/lib` | Low
31 | File | `/librarian/lab.php` | High
32 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
33 | File | `/modules/projects/vw_files.php` | High
34 | File | `/mtms/admin/?page=transaction/send` | High
35 | File | `/net-banking/send_funds.php` | High
36 | File | `/nova/bin/igmp-proxy` | High
37 | File | `/odlms/?page=appointments/view_appointment` | High
38 | File | `/out.php` | Medium
39 | File | `/picturesPreview` | High
40 | File | `/purchase_order/admin/?page=system_info` | High
41 | File | `/ram/pckg/advanced-tools/nova/bin/netwatch` | High
42 | ... | ... | ...

There are 364 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
