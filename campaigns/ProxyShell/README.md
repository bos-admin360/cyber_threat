# ProxyShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyShell:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 26 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyShell. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyShell. This data is unique as it uses our predictive model for actor profiling.

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
20 | File | `/filemanager/upload.php` | High
21 | File | `/forum/away.php` | High
22 | File | `/goforms/rlminfo` | High
23 | File | `/HNAP1/SetClientInfo` | High
24 | File | `/index_amp.php` | High
25 | File | `/Items/*/RemoteImages/Download` | High
26 | File | `/login` | Low
27 | File | `/menu.html` | Medium
28 | File | `/navigate/navigate_download.php` | High
29 | File | `/ocwbs/admin/?page=user/manage_user` | High
30 | File | `/ofrs/admin/?page=user/manage_user` | High
31 | File | `/out.php` | Medium
32 | File | `/owa/auth/logon.aspx` | High
33 | File | `/password.html` | High
34 | File | `/php_action/fetchSelectedUser.php` | High
35 | File | `/proc/ioports` | High
36 | File | `/property-list/property_view.php` | High
37 | File | `/ptms/classes/Users.php` | High
38 | File | `/resources//../` | High
39 | File | `/rest/api/2/search` | High
40 | File | `/s/` | Low
41 | File | `/scripts/cpan_config` | High
42 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
43 | File | `/services/system/setup.json` | High
44 | File | `/spip.php` | Medium
45 | File | `/sys/dict/queryTableData` | High
46 | File | `/tmp` | Low
47 | File | `/uncpath/` | Medium
48 | File | `/vloggers_merch/?p=view_product` | High
49 | File | `/webconsole/APIController` | High
50 | ... | ... | ...

There are 432 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
