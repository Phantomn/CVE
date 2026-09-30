# CVE

Vulnerabilities I found and reported, with write-ups and PoCs. Each directory is one CVE.

## Embedded devices (2024-2025)

Found with [CoreSecurity](https://www.coresec.co.kr/) (OT/ICS and embedded).

| CVE | Target | Bug type |
|-----|--------|----------|
| [CVE-2024-33788](CVE-2024-33788) | Linksys E5600 | Command Injection |
| [CVE-2024-33789](CVE-2024-33789) | Linksys E5600 | Command Injection |
| [CVE-2024-33791](CVE-2024-33791) | netis MEX605 | Cross Site Scripting |
| [CVE-2024-33792](CVE-2024-33792) | netis MEX605 | Command Injection |
| [CVE-2024-33793](CVE-2024-33793) | netis MEX605 | Command Injection |
| [CVE-2025-55423](CVE-2025-55423) | ipTIME routers (163 models) | Command Injection |

## Linux kernel filesystems (2019)

Found during the [BoB](https://www.kitribob.kr/) project "bobfuzzer" by fuzzing kernel filesystem modules.

[CVE-2019-18885](CVE-2019-18885), [CVE-2019-19036](CVE-2019-19036), [CVE-2019-19037](CVE-2019-19037), [CVE-2019-19039](CVE-2019-19039), [CVE-2019-19318](CVE-2019-19318), [CVE-2019-19319](CVE-2019-19319), [CVE-2019-19377](CVE-2019-19377), [CVE-2019-19378](CVE-2019-19378), [CVE-2019-19447](CVE-2019-19447), [CVE-2019-19448](CVE-2019-19448), [CVE-2019-19449](CVE-2019-19449), [CVE-2019-19813](CVE-2019-19813), [CVE-2019-19814](CVE-2019-19814), [CVE-2019-19815](CVE-2019-19815), [CVE-2019-19816](CVE-2019-19816), [CVE-2019-19927](CVE-2019-19927)

The fuzzer was a port (to Linux 5.0.21 and 5.3.14) of JANUS by GeorgiaTech SSLab.

* [sslab-gatech/janus](https://github.com/sslab-gatech/janus)
* [Fuzzing File Systems via Two-Dimensional Input Space Exploration (IEEE S&P 2019)](https://gts3.org/assets/papers/2019/xu:janus.pdf)

## Credits

* 2019 (bobfuzzer): Kieast, zkaryaJo, Ph4nt0m, NJhyo, nonetype. Leader DelspoN. Mentors k1rh4, Ashine.
* 2024-2025 (CoreSecurity): Ph4nt0m, pinebudweiser, Turtle3, isj, rhenus. Leader mkyoon.
