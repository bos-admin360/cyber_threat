# APT3 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT3](https://vuldb.com/?actor.apt3). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt3](https://vuldb.com/?actor.apt3)

## Campaigns

The following _campaigns_ are known and can be associated with APT3:

* CVE-2015-5119
* Double Tap

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT3:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT3.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.99.20.198](https://vuldb.com/?ip.23.99.20.198) | - | - | High
2 | [54.169.89.240](https://vuldb.com/?ip.54.169.89.240) | ec2-54-169-89-240.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [104.151.248.173](https://vuldb.com/?ip.104.151.248.173) | 173.248-151-104.rdns.scalabledns.com | Double Tap | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT3_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT3. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/admin/default.asp` | High
4 | File | `/ajax/networking/get_netcfg.php` | High
5 | File | `/app/options.py` | High
6 | File | `/bin/httpd` | Medium
7 | File | `/cgi-bin/wapopen` | High
8 | File | `/ci_spms/admin/category` | High
9 | File | `/ci_spms/admin/search/searching/` | High
10 | File | `/classes/Master.php?f=delete_appointment` | High
11 | File | `/classes/Master.php?f=delete_train` | High
12 | File | `/cms/print.php` | High
13 | File | `/concat?/%2557EB-INF/web.xml` | High
14 | File | `/Content/Template/root/reverse-shell.aspx` | High
15 | File | `/ctcprotocol/Protocol` | High
16 | File | `/dashboard/menu-list.php` | High
17 | File | `/data/remove` | Medium
18 | File | `/ebics-server/ebics.aspx` | High
19 | File | `/ffos/classes/Master.php?f=save_category` | High
20 | File | `/forum/away.php` | High
21 | File | `/goforms/rlminfo` | High
22 | File | `/HNAP1/SetClientInfo` | High
23 | File | `/Items/*/RemoteImages/Download` | High
24 | File | `/login` | Low
25 | File | `/menu.html` | Medium
26 | File | `/navigate/navigate_download.php` | High
27 | File | `/ocwbs/admin/?page=user/manage_user` | High
28 | File | `/ofrs/admin/?page=user/manage_user` | High
29 | File | `/out.php` | Medium
30 | File | `/owa/auth/logon.aspx` | High
31 | File | `/password.html` | High
32 | File | `/php_action/fetchSelectedUser.php` | High
33 | File | `/proc/ioports` | High
34 | File | `/property-list/property_view.php` | High
35 | File | `/ptms/classes/Users.php` | High
36 | File | `/resources//../` | High
37 | File | `/rest/api/2/search` | High
38 | File | `/s/` | Low
39 | File | `/scripts/cpan_config` | High
40 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
41 | File | `/services/system/setup.json` | High
42 | File | `/spip.php` | Medium
43 | File | `/sys/dict/queryTableData` | High
44 | File | `/tmp` | Low
45 | File | `/uncpath/` | Medium
46 | File | `/vloggers_merch/?p=view_product` | High
47 | File | `/webconsole/APIController` | High
48 | File | `/websocket/exec` | High
49 | ... | ... | ...

There are 429 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fireeye/iocs/blob/master/APT3/62f65dae-9475-44b0-a9eb-c1baebbd9885.ioc
* https://github.com/fireeye/iocs/blob/master/APT3/db0b6ac6-874a-498e-892b-ac7c2020e061.ioc
* https://www.fireeye.com/blog/threat-research/2014/11/operation_doubletap.html
* https://www.fireeye.com/blog/threat-research/2015/07/demonstrating_hustle.html
* https://www.recordedfuture.com/chinese-mss-behind-apt3/
* https://www.threatminer.org/report.php?q=APTGroupUPSTargetsUSGovernmentwithHackingTeamFlashExploit-PaloAltoNetworksBlogPaloAltoNetworksBlog.pdf&y=2015
* https://www.threatminer.org/report.php?q=OperationDoubleTap.pdf&y=2014
* https://www.threatminer.org/report.php?q=SecondAdobeFlashZero-DayCVE-2015-5122fromHackingTeamExploitedinStrategicWebCompromiseTargetingJapaneseVictims%C2%ABThreatResearchBlog_FireEyeInc.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
