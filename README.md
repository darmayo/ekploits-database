<div align="center">

# 🧩 Exploit Databases & Vulnerability Intelligence

**Koleksi exploit databases, vulnerability databases, CVE references, public exposure search engines, PoC collections, payload references, dan threat intelligence resources untuk security research, vulnerability validation, patch verification, bug bounty legal, dan defensive security.**

![Focus](https://img.shields.io/badge/focus-exploit%20database%20%7C%20CVE%20%7C%20PoC-7F77DD?style=flat-square)
![Usage](https://img.shields.io/badge/usage-ethical%20only-D85A30?style=flat-square)
![Category](https://img.shields.io/badge/category-vulnerability%20research%20%7C%20defensive%20validation-1D9E75?style=flat-square)

</div>

---

> Repository ini dibuat sebagai katalog referensi, bukan untuk menyerang target tanpa izin.  
> Gunakan hanya untuk lab, CTF, bug bounty yang jelas scope-nya, internal pentest berizin, patch verification, detection engineering, dan defensive research.

---

## 📑 Daftar Isi

- [🎯 Purpose](#-purpose)
- [🧩 Primary Exploit Databases](#-primary-exploit-databases)
- [🛡️ CVE & Vulnerability Databases](#️-cve--vulnerability-databases)
- [🌍 Internet Exposure & Attack Surface Search Engines](#-internet-exposure--attack-surface-search-engines)
- [🧪 PoC Collections & Exploit Research Repositories](#-poc-collections--exploit-research-repositories)
- [🧰 Exploit Frameworks & Local Search Tools](#-exploit-frameworks--local-search-tools)
- [📦 Payload & Technique References](#-payload--technique-references)
- [🚨 Known Exploited Vulnerabilities & Threat Intelligence](#-known-exploited-vulnerabilities--threat-intelligence)
- [🧭 Research Workflow](#-research-workflow)
- [🚫 Unverified / Parked / Not Recommended](#-unverified--parked--not-recommended)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🎯 Purpose

Exploit database digunakan untuk mencari referensi vulnerability, exploit proof-of-concept, CVE detail, affected versions, patch information, public advisories, dan teknik validasi keamanan.

Use cases yang aman:

- Patch verification
- Vulnerability research
- Internal pentest berizin
- Bug bounty sesuai scope
- Lab/CTF
- Detection engineering
- SOC enrichment
- Threat intelligence
- Writing remediation guidance

---

## 🧩 Primary Exploit Databases

| Resource | Link | Fungsi |
|---|---|---|
| Exploit-DB | https://www.exploit-db.com/ | Public exploit archive dari OffSec, banyak dipakai untuk vulnerability research dan referensi PoC. |
| Packet Storm Security | https://packetstorm.news/ | Archive security tools, exploits, advisories, whitepapers, dan security research. |
| Rapid7 Vulnerability & Exploit Database | https://www.rapid7.com/db/ | Database vulnerability dan exploit yang berhubungan dengan ekosistem Metasploit/Rapid7. |
| 0day.today | https://0day.today/ | Exploit marketplace/database; gunakan hanya sebagai referensi riset dan hati-hati dengan konten berisiko. |
| CXSecurity | https://cxsecurity.com/exploit/ | Exploit and vulnerability disclosure archive. |
| Sploitus | https://sploitus.com/ | Search engine untuk exploit dan PoC dari berbagai sumber publik. |
| Vulners Exploit Search | https://vulners.com/search | Vulnerability intelligence search engine dengan banyak sumber exploit/advisory. |

---

## 🛡️ CVE & Vulnerability Databases

| Resource | Link | Fungsi |
|---|---|---|
| CVE | https://www.cve.org/ | Catalog resmi untuk publicly disclosed cybersecurity vulnerabilities. |
| NVD | https://nvd.nist.gov/vuln | National Vulnerability Database untuk CVE detail, CVSS, CPE, reference, dan enrichment. |
| Vulners | https://vulners.com/ | Vulnerability intelligence database dan search engine. |
| VulDB | https://vuldb.com/ | Vulnerability database dan threat intelligence platform. |
| GitHub Security Advisories | https://github.com/advisories | Advisory database untuk vulnerability pada package dan GitHub ecosystem. |
| GitLab Advisory Database | https://advisories.gitlab.com/ | Advisory database untuk dependency/package vulnerabilities. |
| OSV | https://osv.dev/ | Open Source Vulnerabilities database untuk ecosystem package open-source. |
| Snyk Vulnerability DB | https://security.snyk.io/ | Vulnerability database untuk open-source dependencies, container, IaC, dan package ecosystem. |
| Mend Vulnerability Database | https://www.mend.io/vulnerability-database/ | Database vulnerability untuk open-source components. |
| Red Hat CVE Database | https://access.redhat.com/security/security-updates/#/cve | CVE database dan security updates dari Red Hat. |
| Ubuntu Security Notices | https://ubuntu.com/security/notices | Security notices dan CVE tracking untuk Ubuntu. |
| Debian Security Tracker | https://security-tracker.debian.org/tracker/ | CVE/security tracker untuk Debian packages. |
| Microsoft Security Response Center | https://msrc.microsoft.com/update-guide/vulnerability | Microsoft vulnerability update guide. |
| Apple Security Releases | https://support.apple.com/en-us/100100 | Apple security updates and releases. |
| Android Security Bulletins | https://source.android.com/docs/security/bulletin | Android security bulletin dan patch information. |

---

## 🌍 Internet Exposure & Attack Surface Search Engines

| Resource | Link | Fungsi |
|---|---|---|
| Shodan | https://www.shodan.io/ | Search engine untuk internet-connected devices, services, banners, ports, dan exposed assets. |
| Censys | https://search.censys.io/ | Search engine untuk internet hosts, certificates, ports, protocols, dan exposure. |
| FOFA | https://fofa.info/ | Attack surface search engine. |
| ZoomEye | https://www.zoomeye.org/ | Cyberspace search engine untuk exposed assets dan services. |
| Netlas | https://netlas.io/ | Internet asset search engine untuk DNS, IP, certificates, ports, dan web exposure. |
| LeakIX | https://leakix.net/ | Search engine untuk exposed services, leaks, dan misconfigurations. |
| GreyNoise | https://www.greynoise.io/ | Internet scanning/noise intelligence untuk membedakan opportunistic scanning dan threat activity. |
| BinaryEdge | https://www.binaryedge.io/ | Internet scanning dan threat intelligence. |
| ONYPHE | https://www.onyphe.io/ | Cyber defense search engine untuk exposed assets dan threat intelligence. |
| Criminal IP | https://www.criminalip.io/ | Attack surface intelligence dan asset risk search. |
| urlscan.io | https://urlscan.io/ | URL/website scan archive, DOM, request, screenshot, dan infrastructure intelligence. |
| SecurityTrails | https://securitytrails.com/ | DNS, domain, subdomain, dan historical DNS intelligence. |
| crt.sh | https://crt.sh/ | Certificate Transparency search untuk domain/subdomain discovery. |
| PublicWWW | https://publicwww.com/ | Source code search engine untuk HTML/JS/CSS public web content. |

---

## 🧪 PoC Collections & Exploit Research Repositories

| Resource | Link | Fungsi |
|---|---|---|
| ProjectDiscovery Nuclei Templates | https://github.com/projectdiscovery/nuclei-templates | Detection templates untuk CVE, exposure, misconfiguration, dan vulnerability checks. |
| Awesome CVE PoC | https://github.com/qazbnm456/awesome-cve-poc | Curated CVE PoC references. |
| 0xMarcio CVE | https://github.com/0xMarcio/cve | Koleksi PoC CVE untuk riset/lab. |
| rainpwn exploits | https://github.com/rainpwn/exploits | Koleksi exploit/PoC untuk riset lab legal. |
| chebuya exploits | https://github.com/chebuya/exploits | Koleksi exploit/PoC security research. |
| vulnerability research awesome | https://github.com/re-pronin/awesome-vulnerability-research | Resource vulnerability research. |
| awesome exploit development | https://github.com/FabioBaroni/awesome-exploit-development | Resource exploit development. |
| Metasploit Framework | https://github.com/rapid7/metasploit-framework | Framework exploit development, validation, dan module-based security testing untuk lab/legal scope. |
| Exploit Database GitLab Mirror | https://gitlab.com/exploit-database/exploitdb | Mirror/repository untuk Exploit-DB. |

---

## 🧰 Exploit Frameworks & Local Search Tools

| Tool | Link | Fungsi |
|---|---|---|
| Searchsploit | https://www.kali.org/tools/exploitdb/ | CLI untuk mencari Exploit-DB secara lokal di Kali Linux. |
| Metasploit Framework | https://github.com/rapid7/metasploit-framework | Framework untuk exploit modules, auxiliary modules, post-exploitation lab, dan validation legal. |
| Nuclei | https://github.com/projectdiscovery/nuclei | Template-based scanner untuk CVE/misconfiguration detection. |
| Nmap NSE Scripts | https://nmap.org/nsedoc/ | Nmap Scripting Engine untuk enumeration dan vulnerability checks. |
| Wapiti | https://github.com/wapiti-scanner/wapiti | Web application vulnerability scanner. |
| Nikto | https://github.com/sullo/nikto | Web server scanner klasik. |
| Greenbone / OpenVAS | https://github.com/greenbone/gvmd | Vulnerability scanning dan management platform. |
| Trivy | https://github.com/aquasecurity/trivy | Vulnerability/misconfiguration scanner untuk container, filesystem, IaC, Kubernetes, dan secrets. |
| Vuls | https://github.com/future-architect/vuls | Agentless vulnerability scanner untuk Linux/FreeBSD servers. |

---

## 📦 Payload & Technique References

| Resource | Link | Fungsi |
|---|---|---|
| PayloadsAllTheThings | https://github.com/swisskyrepo/PayloadsAllTheThings | Payload, bypass, dan technique references untuk banyak vulnerability class. |
| HackTricks | https://book.hacktricks.xyz/ | Pentest notes, technique references, cloud, web, Linux/Windows, privilege escalation, dan more. |
| GTFOBins | https://gtfobins.github.io/ | Unix binaries abuse reference untuk privilege escalation/lab. |
| LOLBAS | https://lolbas-project.github.io/ | Windows living-off-the-land binaries/scripts/libraries reference. |
| WADComs | https://wadcoms.github.io/ | Windows/AD command reference untuk internal assessment. |
| PayloadBox | https://github.com/payloadbox | Payload collections untuk web vulnerability testing. |
| SecLists | https://github.com/danielmiessler/SecLists | Wordlists dan payload lists untuk security testing. |

---

## 🚨 Known Exploited Vulnerabilities & Threat Intelligence

| Resource | Link | Fungsi |
|---|---|---|
| CISA Known Exploited Vulnerabilities Catalog | https://www.cisa.gov/known-exploited-vulnerabilities-catalog | Catalog vulnerability yang diketahui sudah dieksploitasi di dunia nyata. |
| Google Project Zero | https://googleprojectzero.blogspot.com/ | Vulnerability research dan exploit analysis. |
| Google TAG Blog | https://blog.google/threat-analysis-group/ | Threat analysis, exploitation campaigns, dan threat actor reporting. |
| Microsoft Security Blog | https://www.microsoft.com/en-us/security/blog/ | Security research, threat intelligence, dan vulnerability exploitation trends. |
| Mandiant Blog | https://www.mandiant.com/resources/blog | Threat intelligence, intrusion analysis, exploitation, dan incident response research. |
| Unit 42 Threat Research | https://unit42.paloaltonetworks.com/ | Threat intelligence dan vulnerability exploitation analysis. |
| Cisco Talos Blog | https://blog.talosintelligence.com/ | Threat research, malware, vulnerabilities, dan exploitation trends. |
| Rapid7 Blog | https://www.rapid7.com/blog/ | Vulnerability research, exploit analysis, dan security operations insights. |

---

## 🧭 Research Workflow

```text
1. Identify product / version / component
   ↓
2. Search CVE / NVD / vendor advisory
   ↓
3. Check exploit databases and PoC references
   ↓
4. Verify affected versions and patch status
   ↓
5. Reproduce only in lab or authorized scope
   ↓
6. Document evidence, impact, and mitigation
   ↓
7. Build detection / hardening / patch recommendation
```

### Safe Query Examples

```text
site:exploit-db.com Apache 2.4 CVE
site:packetstorm.news CVE-2024
site:github.com CVE-2025 PoC
site:nvd.nist.gov CVE product version
site:cisa.gov known exploited vulnerabilities product
```

---

## 🚫 Unverified / Parked / Not Recommended

| Resource | Link | Catatan |
|---|---|---|
| intelligentexploit.com via HugeDomains | https://www.hugedomains.com/domain_profile.cfm?d=intelligentexploit.com | Link ini terlihat seperti domain profile/penjualan domain, bukan exploit database aktif. Simpan hanya sebagai catatan, bukan resource utama. |

---

## ⚖️ Disclaimer

Gunakan semua database dan referensi ini hanya untuk:

- Lab pribadi
- CTF
- Bug bounty sesuai scope
- Internal pentest berizin
- Patch verification
- Detection engineering
- Malware/vulnerability research legal
- Defensive security
- Security education

Jangan menggunakan exploit, PoC, payload, scanner, search engine, atau teknik dari resource ini untuk menyerang, mengeksploitasi, memindai, mengambil data, membuat persistence, melakukan credential theft, atau mengakses sistem pihak lain tanpa izin eksplisit.

Repository ini adalah katalog referensi untuk pembelajaran dan riset keamanan yang etis.
