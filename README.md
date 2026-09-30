# CVE

Vulnerabilities I found and reported, with write-ups and PoCs. Each directory is one CVE.

---

## CoreSecurity (2024-2025)

Our team [CoreSecurity](https://www.coresec.co.kr/) in Republic of Korea. ([coresec@coresec.co.kr](mailto:coresec@coresec.co.kr))

finding bugs in OT/ICS Area

### Team Members
**Member**: 홍승표([Ph4nt0m](https://github.com/Phantomn)), 배대식([pinebudweiser](https://github.com/pinebudweiser)), 임은서([Turtle3](https://github.com/turt1e3)), 조이수([isj](https://github.com/W0rldwide)), 배정훈([rhenus](https://github.com/rhenus9911))

**Leader**: 윤민규([mkyoon](https://github.com/ymkyu))

### CVEs

| CVE | Target | Bug type |
|-----|--------|----------|
| [CVE-2024-33788](CVE-2024-33788) | Linksys E5600 | Command Injection |
| [CVE-2024-33789](CVE-2024-33789) | Linksys E5600 | Command Injection |
| [CVE-2024-33791](CVE-2024-33791) | netis MEX605 | Cross Site Scripting |
| [CVE-2024-33792](CVE-2024-33792) | netis MEX605 | Command Injection |
| [CVE-2024-33793](CVE-2024-33793) | netis MEX605 | Command Injection |
| [CVE-2025-55423](CVE-2025-55423) | ipTIME routers (163 models) | Command Injection |

---

## bobfuzzer (2019)

project team in BoB(a.k.a [Best of the Best](https://www.kitribob.kr/)) in Republic of Korea. ([bobfuzzer@gmail.com](mailto:bobfuzzer@gmail.com))

finding bugs in linux kernel filesystem modules

### Team Members
**Project Member**: 김동희([Kieast](https://github.com/Kieast)), 조형진([zkaryaJo](https://github.com/zkaryaJo)), 홍승표([Ph4nt0m](https://github.com/Phantomn)), 남지효([NJhyo](https://github.com/NJhyo)), 정원영([nonetype](https://github.com/nonetype))

**Project Leader**: 조성준([DelspoN](https://github.com/delspon))

**Project Mentor**: 이상섭([k1rh4](https://github.com/k1rh4)), 박천성([Ashine](https://github.com/ash1n2/))

### CVEs

[CVE-2019-18885](CVE-2019-18885), [CVE-2019-19036](CVE-2019-19036), [CVE-2019-19037](CVE-2019-19037), [CVE-2019-19039](CVE-2019-19039), [CVE-2019-19318](CVE-2019-19318), [CVE-2019-19319](CVE-2019-19319), [CVE-2019-19377](CVE-2019-19377), [CVE-2019-19378](CVE-2019-19378), [CVE-2019-19447](CVE-2019-19447), [CVE-2019-19448](CVE-2019-19448), [CVE-2019-19449](CVE-2019-19449), [CVE-2019-19813](CVE-2019-19813), [CVE-2019-19814](CVE-2019-19814), [CVE-2019-19815](CVE-2019-19815), [CVE-2019-19816](CVE-2019-19816), [CVE-2019-19927](CVE-2019-19927)

### Acknowledgments
This Project used ported version(to 5.0.21 and 5.3.14 linux kernel) of filesystem fuzzer 'JANUS' which developed by GeorgiaTech Systems Software & Security Lab(SSLab)

Thank you for the excellent fuzzer and paper below.

* [sslab-gatech/janus](https://github.com/sslab-gatech/janus)
* [Fuzzing File Systems via Two-Dimensional Input Space Exploration (IEEE S&P 2019)](https://gts3.org/assets/papers/2019/xu:janus.pdf)
