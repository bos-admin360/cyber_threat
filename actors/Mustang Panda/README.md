# Mustang Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mustang Panda](https://vuldb.com/?actor.mustang_panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mustang_panda](https://vuldb.com/?actor.mustang_panda)

## Campaigns

The following _campaigns_ are known and can be associated with Mustang Panda:

* Diànxùn
* Europe
* Europe and Asia Pacific
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mustang Panda:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mustang Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.228.54.173](https://vuldb.com/?ip.3.228.54.173) | ec2-3-228-54-173.compute-1.amazonaws.com | - | Medium
2 | [5.34.178.156](https://vuldb.com/?ip.5.34.178.156) | paulojohnjerick.pserver.ru | Europe and Asia Pacific | High
3 | [5.206.224.167](https://vuldb.com/?ip.5.206.224.167) | hardsysi | Europe | High
4 | [18.138.107.235](https://vuldb.com/?ip.18.138.107.235) | ec2-18-138-107-235.ap-southeast-1.compute.amazonaws.com | Europe | Medium
5 | [42.99.117.95](https://vuldb.com/?ip.42.99.117.95) | - | - | High
6 | [43.254.217.67](https://vuldb.com/?ip.43.254.217.67) | - | - | High
7 | [43.254.218.42](https://vuldb.com/?ip.43.254.218.42) | - | Hodur | High
8 | [43.254.218.128](https://vuldb.com/?ip.43.254.218.128) | - | Europe and Asia Pacific | High
9 | [45.32.50.150](https://vuldb.com/?ip.45.32.50.150) | 45.32.50.150.vultr.com | - | Medium
10 | [45.32.101.7](https://vuldb.com/?ip.45.32.101.7) | 45.32.101.7.vultrusercontent.com | Europe and Asia Pacific | High
11 | [45.43.50.197](https://vuldb.com/?ip.45.43.50.197) | - | Europe | High
12 | [45.77.184.12](https://vuldb.com/?ip.45.77.184.12) | comm.phiu.pw | - | High
13 | [45.131.179.179](https://vuldb.com/?ip.45.131.179.179) | - | Hodur | High
14 | [45.134.83.4](https://vuldb.com/?ip.45.134.83.4) | - | - | High
15 | [45.134.83.41](https://vuldb.com/?ip.45.134.83.41) | - | PlugX | High
16 | [45.147.26.45](https://vuldb.com/?ip.45.147.26.45) | - | Europe and Asia Pacific | High
17 | [45.154.14.235](https://vuldb.com/?ip.45.154.14.235) | - | Hodur | High
18 | ... | ... | ... | ...

There are 68 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mustang Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mustang Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/admin/?page=orders/manage_request` | High
3 | File | `/admin/settings.php` | High
4 | File | `/admin/uploads.php` | High
5 | File | `/api/geojson` | Medium
6 | File | `/api/user/password/sent-reset-email` | High
7 | File | `/api/v1/attack` | High
8 | File | `/cgi-bin/portal` | High
9 | File | `/Config/service/initModel?` | High
10 | File | `/data/config.ftp.php` | High
11 | File | `/etc/shadow` | Medium
12 | File | `/export` | Low
13 | File | `/goform/NTPSyncWithHost` | High
14 | File | `/goform/SetVirtualServerCfg` | High
15 | File | `/HNAP1/SetAccessPointMode` | High
16 | File | `/home/<user>/SecurityOnion/setup/so-setup` | High
17 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
18 | File | `/htmlcode/html/indexdefault.asp` | High
19 | File | `/include/helpers/upload.helper.php` | High
20 | File | `/interface/main/backup.php` | High
21 | File | `/local/domain/$DOMID` | High
22 | File | `/mkshop/Men/profile.php` | High
23 | File | `/MTFWU` | Low
24 | File | `/mygym/admin/index.php` | High
25 | File | `/opt/Citrix/ICAClient/util/ctxwebhelper` | High
26 | File | `/patient/settings.php` | High
27 | File | `/product/savenewproduct.php?flag=1` | High
28 | ... | ... | ...

There are 239 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/05/mustang-panda-targets-europe.html
* https://blogs.blackberry.com/en/2022/10/mustang-panda-abuses-legitimate-apps-to-target-myanmar-based-victims
* https://blogs.blackberry.com/en/2022/12/mustang-panda-uses-the-russian-ukrainian-war-to-attack-europe-and-asia-pacific-targets
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q2
* https://twitter.com/ESETresearch/status/1400165861973966854
* https://twitter.com/xorhex/status/1406496693735067650
* https://twitter.com/xorhex/status/1422815329684758537
* https://www.anomali.com/blog/china-based-apt-mustang-panda-targets-minority-groups-public-and-private-sector-organizations
* https://www.mcafee.com/enterprise/en-us/assets/reports/rp-operation-dianxun.pdf
* https://www.secureworks.com/blog/bronze-president-targets-russian-speakers-with-updated-plugx
* https://www.welivesecurity.com/2022/03/23/mustang-panda-hodur-old-tricks-new-korplug-variant/
* https://www.welivesecurity.com/2023/03/02/mqsttang-mustang-panda-latest-backdoor-treads-new-ground-qt-mqtt/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
