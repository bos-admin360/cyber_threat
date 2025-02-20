# StreamEx - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _StreamEx_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StreamEx:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with StreamEx or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StreamEx.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
2 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
3 | [88.208.228.56](https://vuldb.com/?ip.88.208.228.56) | bextec.co.uk | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within StreamEx. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during StreamEx. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin/submit-articles` | High
4 | File | `/ad_js.php` | Medium
5 | File | `/Ap4RtpAtom.cpp` | High
6 | File | `/app/options.py` | High
7 | File | `/attachments` | Medium
8 | File | `/bcms/admin/?page=user/list` | High
9 | File | `/bsms/?page=manage_account` | High
10 | File | `/cgi-bin/login.cgi` | High
11 | File | `/cgi-bin/luci/api/wireless` | High
12 | File | `/ci_hms/massage_room/edit/1` | High
13 | File | `/context/%2e/WEB-INF/web.xml` | High
14 | File | `/dashboard/reports/logs/view` | High
15 | File | `/debian/patches/load_ppp_generic_if_needed` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/etc/hosts` | Medium
18 | File | `/fuel/sitevariables/delete/4` | High
19 | File | `/goform/setmac` | High
20 | File | `/goform/wizard_end` | High
21 | File | `/hprms/admin/doctors/manage_doctor.php` | High
22 | File | `/index/jobfairol/show/` | High
23 | File | `/librarian/bookdetails.php` | High
24 | File | `/manage-apartment.php` | High
25 | File | `/mgmt/tm/util/bash` | High
26 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
27 | File | `/pages/apply_vacancy.php` | High
28 | File | `/proc/<PID>/mem` | High
29 | File | `/proxy` | Low
30 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
31 | File | `/spip.php` | Medium
32 | File | `/tmp` | Low
33 | ... | ... | ...

There are 279 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
