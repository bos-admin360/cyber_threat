# Pegasus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Pegasus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pegasus:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Pegasus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [NSO Group](https://vuldb.com/?actor.nso_group) | High
2 | [LULU](https://vuldb.com/?actor.lulu) | High
3 | [Sarwent](https://vuldb.com/?actor.sarwent) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pegasus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.13.132.96](https://vuldb.com/?ip.3.13.132.96) | ec2-3-13-132-96.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
2 | [3.16.75.157](https://vuldb.com/?ip.3.16.75.157) | ec2-3-16-75-157.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
3 | [13.58.85.100](https://vuldb.com/?ip.13.58.85.100) | ec2-13-58-85-100.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
4 | [13.59.79.240](https://vuldb.com/?ip.13.59.79.240) | ec2-13-59-79-240.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
5 | [18.191.63.125](https://vuldb.com/?ip.18.191.63.125) | ec2-18-191-63-125.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
6 | [18.217.13.50](https://vuldb.com/?ip.18.217.13.50) | ec2-18-217-13-50.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
7 | [18.225.12.72](https://vuldb.com/?ip.18.225.12.72) | ec2-18-225-12-72.us-east-2.compute.amazonaws.com | [NSO Group](https://vuldb.com/?actor.nso_group) | Medium
8 | [23.239.16.143](https://vuldb.com/?ip.23.239.16.143) | li685-143.members.linode.com | [NSO Group](https://vuldb.com/?actor.nso_group) | High
9 | [45.32.105.249](https://vuldb.com/?ip.45.32.105.249) | 45.32.105.249.vultrusercontent.com | [NSO Group](https://vuldb.com/?actor.nso_group) | High
10 | [45.79.190.38](https://vuldb.com/?ip.45.79.190.38) | srv01.benlinden.com | [NSO Group](https://vuldb.com/?actor.nso_group) | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Pegasus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Pegasus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit_visitor.php` | High
2 | File | `/admin/info.php` | High
3 | File | `/admin/user_list_backend.php` | High
4 | File | `/apply.cgi` | Medium
5 | File | `/etc/controller-agent/agent.conf` | High
6 | File | `/forms/web_importTFTP` | High
7 | File | `/goform/SysToolReboot` | High
8 | File | `/goform/SysToolRestoreSet` | High
9 | File | `/graphql` | Medium
10 | File | `/individual` | Medium
11 | File | `/jeecg-boot/jmreport/view` | High
12 | File | `/jsoa/hntdCustomDesktopActionContent` | High
13 | File | `/localhost/u` | Medium
14 | File | `/net` | Low
15 | File | `/opt/bin/cli` | Medium
16 | File | `/PluXml/core/admin/parametres_edittpl.php` | High
17 | File | `/public/plugins/` | High
18 | File | `/public_html/admin/plugins/bad_behavior2/blacklist.php` | High
19 | File | `/root/run/adm.php?admin-ediy&part=exdiy` | High
20 | File | `/setNTP.cgi` | Medium
21 | File | `/templates/header.inc.php` | High
22 | File | `/tmp` | Low
23 | File | `/v2/devices/add` | High
24 | File | `/var/ipfire/backup/bin/backup.pl` | High
25 | File | `/wp-json/wc/v3/webhooks` | High
26 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
27 | File | `account.php` | Medium
28 | File | `accounts/view_details.php` | High
29 | File | `AddEvent.php` | Medium
30 | File | `admin.jcomments.php` | High
31 | File | `admin.php` | Medium
32 | File | `admin.php?m=backup&c=backup&a=doback` | High
33 | File | `admin.php?mod=product&act=state` | High
34 | File | `admin/abc.php` | High
35 | File | `admin/booking_report.php` | High
36 | ... | ... | ...

There are 304 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2021/09/fakeantipegasusamnesty.html
* https://citizenlab.ca/2021/08/bahrain-hacks-activists-with-nso-group-zero-click-iphone-exploits/
* https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
* https://www.amnesty.org/en/latest/research/2021/07/forensic-methodology-report-how-to-catch-nso-groups-pegasus/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
