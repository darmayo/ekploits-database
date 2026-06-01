<div align="center">

# 🧩 Exploit Databases & Vulnerability Intelligence — Complete Edition

**Katalog exploit databases, CVE references, vulnerability databases, public advisories, PoC collections, vulnerability scanners, exposure search engines, payload references, threat intelligence, patch verification, dan defensive validation resources.**

![Focus](https://img.shields.io/badge/focus-exploit%20database%20%7C%20CVE%20%7C%20PoC-7F77DD?style=flat-square)
![Usage](https://img.shields.io/badge/usage-ethical%20only-D85A30?style=flat-square)
![Category](https://img.shields.io/badge/category-vulnerability%20research%20%7C%20defensive%20validation-1D9E75?style=flat-square)
![Resources](https://img.shields.io/badge/resources-174-58a6ff?style=flat-square)

</div>

---

## 📌 Tentang Repo Ini

Fokus repo ini bukan untuk menyerang target, tetapi untuk:

- CVE lookup
- vulnerability validation
- patch verification
- exploitability triage
- detection engineering
- SOC enrichment
- bug bounty legal
- internal pentest berizin
- lab/CTF
- defensive security research
- remediation guidance

Resource yang terlalu high-risk, phishing, backdoor, malware, cracked software, atau automated exploitation dipisahkan ke bagian **Restricted / Not Recommended**.

---

## 📑 Daftar Isi

- [🧩 Primary Exploit Databases & Search Engines](#primary-exploit-databases--search-engines)
- [🛡️ CVE, Vulnerability Databases & Vendor Advisories](#cve-vulnerability-databases--vendor-advisories)
- [🚨 Known Exploited Vulnerabilities & Threat Intelligence](#known-exploited-vulnerabilities--threat-intelligence)
- [🌍 Internet Exposure & Attack Surface Search Engines](#internet-exposure--attack-surface-search-engines)
- [🧪 PoC Collections, CVE Repos & Exploit Research](#poc-collections-cve-repos--exploit-research)
- [🧩 Specific CVE PoC, Advisories & Validation References](#specific-cve-poc-advisories--validation-references)
- [🧰 Local Search, Validation Tools & Vulnerability Scanners](#local-search-validation-tools--vulnerability-scanners)
- [🐳 Dependency, Container, SBOM & Supply Chain Vulnerability Scanning](#dependency-container-sbom--supply-chain-vulnerability-scanning)
- [📦 Payload, Technique References & Fuzzing Resources](#payload-technique-references--fuzzing-resources)
- [📊 Severity Scoring, Triage & Remediation References](#severity-scoring-triage--remediation-references)
- [📚 Learning Labs, Writeups & Vulnerability Practice](#learning-labs-writeups--vulnerability-practice)
- [🚫 Restricted, High-Risk & Not Recommended](#restricted-high-risk--not-recommended)

- [🧭 Safe Vulnerability Research Workflow](#-safe-vulnerability-research-workflow)
- [🔎 Safe Search Query Examples](#-safe-search-query-examples)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🎯 Purpose

Exploit database digunakan untuk mencari referensi vulnerability, exploit proof-of-concept, CVE detail, affected versions, patch information, public advisories, exploitability context, dan teknik validasi keamanan.

Use cases yang aman:

```text
Patch verification
Vulnerability research
Internal pentest berizin
Bug bounty sesuai scope
Lab / CTF
Detection engineering
SOC enrichment
Threat intelligence
Remediation guidance
Security education
```

---

## 🧩 Primary Exploit Databases & Search Engines

| Resource | Link | Fungsi |
|---|---|---|
| Exploit-DB | https://www.exploit-db.com/ | Public exploit archive dari OffSec untuk referensi PoC, advisory, shellcode, dan vulnerability research. |
| Exploit Database GitLab Mirror | https://gitlab.com/exploit-database/exploitdb | Mirror repository Exploit-DB untuk local search dan arsip referensi. |
| Packet Storm Security | https://packetstorm.news/ | Archive security tools, exploits, advisories, whitepapers, dan security research. |
| Rapid7 Vulnerability & Exploit Database | https://www.rapid7.com/db/ | Database vulnerability dan exploit yang terhubung dengan ekosistem Rapid7/Metasploit. |
| 0day.today | https://0day.today/ | Exploit marketplace/database; gunakan hanya sebagai referensi riset dan berhati-hati terhadap konten berisiko. |
| CXSecurity | https://cxsecurity.com/exploit/ | Exploit and vulnerability disclosure archive. |
| Sploitus | https://sploitus.com/ | Search engine untuk exploit dan PoC dari berbagai sumber publik. |
| Vulners Exploit Search | https://vulners.com/search | Search engine vulnerability intelligence dengan exploit/advisory dari banyak sumber. |
| InTheWild.io | https://inthewild.io/ | Referensi eksploitasi in-the-wild dan vulnerability exploitation intelligence. |
| Wiz CVE Database | https://www.wiz.io/vulnerability-database | Vulnerability database dan cloud/security context untuk CVE research. |

---

## 🛡️ CVE, Vulnerability Databases & Vendor Advisories

| Resource | Link | Fungsi |
|---|---|---|
| CVE | https://www.cve.org/ | Catalog resmi untuk publicly disclosed cybersecurity vulnerabilities. |
| NVD | https://nvd.nist.gov/vuln | National Vulnerability Database untuk CVE detail, CVSS, CPE, reference, dan enrichment. |
| CVE Details | https://www.cvedetails.com/ | Searchable CVE database dengan vendor/product/version view. |
| Vulners | https://vulners.com/ | Vulnerability intelligence database dan search engine. |
| VulDB | https://vuldb.com/ | Vulnerability database dan threat intelligence platform. |
| OSV | https://osv.dev/ | Open Source Vulnerabilities database untuk package ecosystem open-source. |
| GitHub Security Advisories | https://github.com/advisories | Advisory database untuk vulnerabilities pada package dan GitHub ecosystem. |
| GitLab Advisory Database | https://advisories.gitlab.com/ | Advisory database untuk dependency/package vulnerabilities. |
| Snyk Vulnerability DB | https://security.snyk.io/ | Vulnerability database untuk open-source dependencies, container, IaC, dan package ecosystem. |
| Mend Vulnerability Database | https://www.mend.io/vulnerability-database/ | Database vulnerability untuk open-source components. |
| Sonatype OSS Index | https://ossindex.sonatype.org/ | Vulnerability intelligence untuk open-source dependencies. |
| Aqua Vulnerability Database | https://avd.aquasec.com/ | Vulnerability database untuk container, Kubernetes, IaC, dan cloud-native ecosystem. |
| Red Hat CVE Database | https://access.redhat.com/security/security-updates/#/cve | CVE database dan security updates dari Red Hat. |
| Ubuntu Security Notices | https://ubuntu.com/security/notices | Security notices dan CVE tracking untuk Ubuntu. |
| Debian Security Tracker | https://security-tracker.debian.org/tracker/ | CVE/security tracker untuk Debian packages. |
| Alpine SecDB | https://secdb.alpinelinux.org/ | Security database untuk Alpine Linux packages. |
| Wolfi SecDB | https://packages.wolfi.dev/os/security.json | Security data untuk Wolfi packages. |
| Microsoft Security Response Center | https://msrc.microsoft.com/update-guide/vulnerability | Microsoft vulnerability update guide. |
| Apple Security Releases | https://support.apple.com/en-us/100100 | Apple security updates and releases. |
| Android Security Bulletins | https://source.android.com/docs/security/bulletin | Android security bulletin dan patch information. |
| Chrome Releases | https://chromereleases.googleblog.com/ | Chrome/Chromium security releases dan update notes. |
| Mozilla Security Advisories | https://www.mozilla.org/en-US/security/advisories/ | Mozilla Firefox dan related product security advisories. |

---

## 🚨 Known Exploited Vulnerabilities & Threat Intelligence

| Resource | Link | Fungsi |
|---|---|---|
| CISA Known Exploited Vulnerabilities Catalog | https://www.cisa.gov/known-exploited-vulnerabilities-catalog | Catalog vulnerability yang diketahui sudah dieksploitasi di dunia nyata. |
| CISA Alerts & Advisories | https://www.cisa.gov/news-events/cybersecurity-advisories | Advisory keamanan dan alert eksploitasi dari CISA. |
| Google Project Zero | https://googleprojectzero.blogspot.com/ | Vulnerability research dan exploit analysis. |
| Google TAG Blog | https://blog.google/threat-analysis-group/ | Threat analysis, exploitation campaigns, dan threat actor reporting. |
| Microsoft Security Blog | https://www.microsoft.com/en-us/security/blog/ | Security research, threat intelligence, dan vulnerability exploitation trends. |
| Mandiant Blog | https://www.mandiant.com/resources/blog | Threat intelligence, intrusion analysis, exploitation, dan incident response research. |
| Unit 42 Threat Research | https://unit42.paloaltonetworks.com/ | Threat intelligence dan vulnerability exploitation analysis. |
| Cisco Talos Blog | https://blog.talosintelligence.com/ | Threat research, malware, vulnerabilities, dan exploitation trends. |
| Rapid7 Blog | https://www.rapid7.com/blog/ | Vulnerability research, exploit analysis, dan security operations insights. |
| Trend Micro ZDI Advisories | https://www.zerodayinitiative.com/advisories/published/ | Zero Day Initiative advisories dan vulnerability disclosure. |
| watchTowr Labs | https://labs.watchtowr.com/ | Research blog untuk vulnerability analysis, exploit chains, dan patch validation. |
| Assetnote Research | https://www.assetnote.io/resources/research | Research AppSec, exposed systems, dan vulnerability analysis. |
| ProjectDiscovery Blog | https://projectdiscovery.io/blog | Research dan engineering notes terkait nuclei/templates/recon/security scanning. |

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
| GreyNoise | https://www.greynoise.io/ | Internet scanning/noise intelligence untuk membedakan scanning oportunistik dan threat activity. |
| BinaryEdge | https://www.binaryedge.io/ | Internet scanning dan threat intelligence. |
| ONYPHE | https://www.onyphe.io/ | Cyber defense search engine untuk exposed assets dan threat intelligence. |
| Criminal IP | https://www.criminalip.io/ | Attack surface intelligence dan asset risk search. |
| urlscan.io | https://urlscan.io/ | URL/website scan archive, DOM, request, screenshot, dan infrastructure intelligence. |
| SecurityTrails | https://securitytrails.com/ | DNS, domain, subdomain, dan historical DNS intelligence. |
| crt.sh | https://crt.sh/ | Certificate Transparency search untuk domain/subdomain discovery. |
| PublicWWW | https://publicwww.com/ | Source code search engine untuk HTML/JS/CSS public web content. |
| DNSDumpster | https://dnsdumpster.com/ | DNS recon dan host discovery. |
| GrayHatWarfare | https://grayhatwarfare.com/ | Public cloud bucket search engine dan exposure intelligence. |
| FullHunt | https://fullhunt.io/ | Attack surface management dan exposure intelligence. |

---

## 🧪 PoC Collections, CVE Repos & Exploit Research

| Resource | Link | Fungsi |
|---|---|---|
| ProjectDiscovery Nuclei Templates | https://github.com/projectdiscovery/nuclei-templates | Detection templates untuk CVE, exposure, misconfiguration, dan vulnerability checks. |
| Nuclei Templates 2026 CVEs | https://github.com/projectdiscovery/nuclei-templates/tree/main/http/cves/2026 | Folder template Nuclei untuk CVE tahun 2026. |
| Nuclei Templates PR 13152 | https://github.com/projectdiscovery/nuclei-templates/pull/13152/files | Referensi logic deteksi Nuclei dari pull request. |
| Awesome CVE PoC | https://github.com/qazbnm456/awesome-cve-poc | Curated CVE PoC references. |
| 0xMarcio CVE | https://github.com/0xMarcio/cve | Koleksi PoC CVE untuk riset/lab. |
| rainpwn exploits | https://github.com/rainpwn/exploits | Koleksi exploit/PoC untuk riset lab legal. |
| chebuya exploits | https://github.com/chebuya/exploits | Koleksi exploit/PoC security research. |
| shadowsock5 Poc | https://github.com/shadowsock5/Poc | Koleksi PoC berbagai produk. |
| rxerium templates | https://github.com/rxerium/rxerium-templates/tree/main/ | Koleksi Nuclei templates. |
| vulnerability research awesome | https://github.com/re-pronin/awesome-vulnerability-research | Resource vulnerability research. |
| awesome exploit development | https://github.com/FabioBaroni/awesome-exploit-development | Resource exploit development. |
| Some-PoC-oR-ExP | https://github.com/coffeehb/Some-PoC-oR-ExP | Koleksi PoC/Exploit untuk research; audit sebelum penggunaan. |
| js-vuln-db | https://github.com/tunz/js-vuln-db | Collection of JavaScript engine CVEs with PoCs. |
| uxss-db | https://github.com/Metnew/uxss-db | Collection of UXSS CVEs with PoCs. |
| nginx-ignition | https://github.com/lucasdillmann/nginx-ignition | Nginx-focused security research/PoC helper; gunakan hanya untuk lab atau validasi patch. |

---

## 🧩 Specific CVE PoC, Advisories & Validation References

| Resource | Link | Fungsi |
|---|---|---|
| Grafana-Final-Scanner | https://github.com/Zierax/Grafana-Final-Scanner | Scanner CVE Grafana untuk lab atau validasi legal. |
| apache-vulnerability-testing | https://github.com/mrmtwoj/apache-vulnerability-testing | Pengujian CVE Apache HTTP Server. |
| nginx-rift | https://github.com/depthfirstdisclosures/nginx-rift | Riset CVE Nginx. |
| Livepyre | https://github.com/synacktiv/Livepyre | Riset CVE Laravel Livewire. |
| cPanelSniper | https://github.com/ynsmroztas/cPanelSniper | PoC cPanel/WHM auth bypass chain. |
| watchTowr cPanel WHM AuthBypass to RCE | https://github.com/watchtowrlabs/watchTowr-vs-cPanel-WHM-AuthBypass-to-RCE.py | PoC cPanel/WHM chain; gunakan hanya untuk lab/validasi patch. |
| CVE-2025-5777 | https://github.com/win3zz/CVE-2025-5777 | PoC/riset CVE-2025-5777 Citrix NetScaler memory leak; lab/legal scope only. |
| CVE-2025-33073 | https://github.com/mverschu/CVE-2025-33073 | PoC CVE-2025-33073 NTLM reflection SMB flaw; lab/legal scope only. |
| Exploit-CVE-2025-24799 | https://github.com/MatheuZSecurity/Exploit-CVE-2025-24799 | PoC/referensi riset CVE-2025-24799 untuk lab atau validasi legal. |
| CVE-2025-55182 React2Shell RCE Shell | https://github.com/M4xSec/CVE-2025-55182-React2Shell-RCE-Shell | PoC React2Shell; simpan sebagai riset/validasi defensif. |
| CVE-2025-55182 advanced scanner | https://github.com/zack0x01/CVE-2025-55182-advanced-scanner- | Scanner React2Shell; gunakan hanya pada scope legal. |
| CVE-2025-55182 shellinteractive | https://github.com/MrR0b0t19/CVE-2025-55182-shellinteractive | PoC interaktif React2Shell; lab/authorized validation only. |
| rschunter | https://github.com/sumanrox/rschunter | Scanner React Server Components CVE hunting. |
| CVE-2025-61882-CVE-2025-61884 | https://github.com/rxerium/CVE-2025-61882-CVE-2025-61884 | Riset Oracle E-Business Suite CVE. |
| CVE-2025-61882 | https://github.com/GhoStZA-debug/CVE-2025-61882 | PoC/referensi CVE-2025-61882; gunakan hanya untuk lab/validasi patch. |
| CVE-2025-61882 Oracle E-Business Suite Pre-Auth RCE Exploit | https://github.com/AdityaBhatt3010/CVE-2025-61882-Oracle-E-Business-Suite-Pre-Auth-RCE-Exploit | PoC/referensi Oracle EBS; gunakan hanya untuk lab atau target berizin. |
| CVE-2025-61884 nuclei template | https://github.com/projectdiscovery/nuclei-templates/blob/main/http%2Fcves%2F2025%2FCVE-2025-61884.yaml | Template deteksi CVE-2025-61884. |
| CVE-2024-21534 | https://github.com/pabloopez/CVE-2024-21534 | PoC/referensi CVE-2024-21534 untuk lab dan validasi patch. |
| CVE-2017-9841-EXPLOIT | https://github.com/K3ysTr0K3R/CVE-2017-9841-EXPLOIT | PoC CVE-2017-9841; gunakan hanya untuk lab/validasi legal. |
| Formbricks GHSA-7229-q9pv-j6p4 | https://github.com/formbricks/formbricks/security/advisories/GHSA-7229-q9pv-j6p4 | Advisory missing JWT signature verification. |
| FreePBX GHSA-m42g-xg4c-5f3h | https://github.com/FreePBX/security-reporting/security/advisories/GHSA-m42g-xg4c-5f3h | Advisory auth bypass → SQLi/RCE. |
| CVE-2025-53652 Jenkins Git Parameter Analysis | https://github.com/pl4tyz/CVE-2025-53652-Jenkins-Git-Parameter-Analysis | Analisis CVE Jenkins Git Parameter. |
| mongobleed | https://github.com/joe-desimone/mongobleed | Riset MongoBleed CVE. |

---

## 🧰 Local Search, Validation Tools & Vulnerability Scanners

| Resource | Link | Fungsi |
|---|---|---|
| Searchsploit | https://www.kali.org/tools/exploitdb/ | CLI untuk mencari Exploit-DB secara lokal di Kali Linux. |
| Metasploit Framework | https://github.com/rapid7/metasploit-framework | Framework exploit modules, auxiliary modules, dan validation legal di lab/scope. |
| Nuclei | https://github.com/projectdiscovery/nuclei | Template-based scanner untuk CVE/misconfiguration detection. |
| Nuclei-AI-Prompts | https://github.com/reewardius/Nuclei-AI-Prompts | Prompt untuk membantu membuat ide deteksi Nuclei. |
| Nmap NSE Scripts | https://nmap.org/nsedoc/ | Nmap Scripting Engine untuk enumeration dan vulnerability checks. |
| Wapiti | https://github.com/wapiti-scanner/wapiti | Web application vulnerability scanner. |
| Nikto | https://github.com/sullo/nikto | Web server scanner klasik. |
| OWASP ZAP | https://github.com/zaproxy/zaproxy | Open-source web/API proxy dan scanner. |
| sqlmap | https://github.com/sqlmapproject/sqlmap | SQL injection automation tool; gunakan hanya pada scope legal. |
| commix | https://github.com/commixproject/commix | Command injection testing tool untuk lab/scope legal. |
| Corsy | https://github.com/s0md3v/Corsy | CORS misconfiguration scanner. |
| SSRFmap | https://github.com/swisskyrepo/SSRFmap | SSRF testing framework untuk lab/scope legal. |
| smugglex | https://github.com/hahwul/smugglex | HTTP Request Smuggling scanner. |
| Trivy | https://github.com/aquasecurity/trivy | Vulnerability, misconfiguration, secret, IaC, container image, Kubernetes, dan filesystem scanner. |
| Grype | https://github.com/anchore/grype | Vulnerability scanner untuk container image dan filesystem. |
| Syft | https://github.com/anchore/syft | SBOM generator untuk container images dan filesystem. |
| Greenbone / OpenVAS | https://github.com/greenbone/gvmd | Vulnerability scanning dan management platform. |
| Vuls | https://github.com/future-architect/vuls | Agentless vulnerability scanner untuk Linux/FreeBSD servers. |
| Clair | https://github.com/quay/clair | Static vulnerability analysis untuk container images. |

---

## 🐳 Dependency, Container, SBOM & Supply Chain Vulnerability Scanning

| Resource | Link | Fungsi |
|---|---|---|
| OSV-Scanner | https://github.com/google/osv-scanner | Scanner dependency vulnerabilities menggunakan OSV database. |
| npm audit | https://docs.npmjs.com/cli/commands/npm-audit | Audit dependency vulnerability untuk Node.js packages. |
| pip-audit | https://github.com/pypa/pip-audit | Audit Python environment dan dependency vulnerabilities. |
| Safety | https://github.com/pyupio/safety | Python dependency vulnerability scanner. |
| Bundler Audit | https://github.com/rubysec/bundler-audit | Ruby Bundler dependency vulnerability scanner. |
| cargo-audit | https://github.com/RustSec/rustsec/tree/main/cargo-audit | Rust dependency vulnerability scanner. |
| govulncheck | https://pkg.go.dev/golang.org/x/vuln/cmd/govulncheck | Go vulnerability checker dari Go team. |
| Dependency-Track | https://github.com/DependencyTrack/dependency-track | Software supply chain component analysis dan vulnerability management platform. |
| CycloneDX | https://github.com/CycloneDX | SBOM standard dan tooling ecosystem. |

---

## 📦 Payload, Technique References & Fuzzing Resources

| Resource | Link | Fungsi |
|---|---|---|
| PayloadsAllTheThings | https://github.com/swisskyrepo/PayloadsAllTheThings | Payload, bypass, dan technique references untuk banyak vulnerability class. |
| PayloadsAllTheThings - Command Injection | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection#filter-bypassesAC | Referensi command injection dan filter bypass. |
| PayloadsAllTheThings - Upload Insecure Files | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Upload%20Insecure%20Files | Referensi bypass upload file dan insecure upload. |
| HackTricks | https://book.hacktricks.xyz/ | Pentest notes, technique references, cloud, web, Linux/Windows, privilege escalation, dan more. |
| GTFOBins | https://gtfobins.github.io/ | Unix binaries abuse reference untuk privilege escalation/lab. |
| LOLBAS | https://lolbas-project.github.io/ | Windows living-off-the-land binaries/scripts/libraries reference. |
| WADComs | https://wadcoms.github.io/ | Windows/AD command reference untuk internal assessment. |
| PayloadBox | https://github.com/payloadbox | Payload collections untuk web vulnerability testing. |
| SecLists | https://github.com/danielmiessler/SecLists | Wordlists dan payload lists untuk security testing. |
| Web-Fuzzing-Box | https://github.com/gh0stkey/Web-Fuzzing-Box | Koleksi dictionary dan payload web fuzzing. |
| XSSNow | https://github.com/dr34mhacks/xssnow | Knowledge base payload XSS. |
| XSS-Payloads | https://github.com/orwagodfather/XSS-Payloads | Koleksi payload XSS. |

---

## 📊 Severity Scoring, Triage & Remediation References

| Resource | Link | Fungsi |
|---|---|---|
| FIRST CVSS | https://www.first.org/cvss/ | Common Vulnerability Scoring System untuk severity scoring. |
| EPSS | https://www.first.org/epss/ | Exploit Prediction Scoring System untuk estimasi probabilitas eksploitasi. |
| SSVC | https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc | Stakeholder-Specific Vulnerability Categorization untuk decision-making patching. |
| CWE | https://cwe.mitre.org/ | Common Weakness Enumeration untuk mapping weakness/root cause. |
| CAPEC | https://capec.mitre.org/ | Common Attack Pattern Enumeration and Classification. |
| ATT&CK | https://attack.mitre.org/ | MITRE ATT&CK matrix untuk adversary behavior dan detection mapping. |
| OWASP Top 10 | https://owasp.org/www-project-top-ten/ | Top 10 risiko web application security. |
| OWASP ASVS | https://owasp.org/www-project-application-security-verification-standard/ | Application Security Verification Standard untuk validation requirements. |
| OWASP API Security Top 10 | https://owasp.org/www-project-api-security/ | Risiko utama API security. |
| OWASP MASVS | https://mas.owasp.org/MASVS/ | Mobile Application Security Verification Standard. |

---

## 📚 Learning Labs, Writeups & Vulnerability Practice

| Resource | Link | Fungsi |
|---|---|---|
| PortSwigger Web Security Academy | https://portswigger.net/web-security | Lab web security gratis untuk belajar vulnerability web modern. |
| OWASP Juice Shop | https://juice-shop.github.io/ | Vulnerable web app modern untuk belajar OWASP Top 10. |
| WebGoat | https://github.com/WebGoat/WebGoat | OWASP vulnerable web application untuk belajar web security. |
| OWASP crAPI | https://github.com/OWASP/crAPI | API lab vulnerable untuk belajar API security. |
| Damn Vulnerable RESTaurant API Game | https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game | API lab vulnerable untuk latihan API security. |
| Hack The Box | https://www.hackthebox.com/ | Platform lab cybersecurity dan skill assessment. |
| TryHackMe | https://tryhackme.com/ | Platform belajar cybersecurity dengan room interaktif. |
| VulnHub | https://www.vulnhub.com/ | Koleksi vulnerable VM untuk latihan pentest lokal. |
| PentesterLab | https://pentesterlab.com/ | Platform latihan web pentest dan code review. |
| Root Me | https://www.root-me.org/ | Platform challenge security. |
| Awesome-Bugbounty-Writeups | https://github.com/devanshbatham/Awesome-Bugbounty-Writeups | Kumpulan writeup bug bounty. |
| HackerOne Reports | https://github.com/reddelexc/hackerone-reports | Kumpulan disclosed HackerOne reports. |
| AllAboutBugBounty | https://github.com/daffainfo/AllAboutBugBounty | Materi dan referensi bug bounty. |

---

## 🚫 Restricted, High-Risk & Not Recommended

> Resource di bagian ini dapat berisiko tinggi, rawan disalahgunakan, tidak relevan untuk repo profesional, atau perlu audit ketat. Simpan hanya sebagai awareness, defensive research, atau lab tertutup bila benar-benar diperlukan.

| Resource | Link | Catatan |
|---|---|---|
| AutoSploit | https://github.com/NullArray/AutoSploit | Automated exploitation framework; high-risk, gunakan hanya untuk lab/legal validation. |
| UFONet | https://github.com/epsylon/ufonet | DDoS/botnet-oriented toolkit; jangan gunakan untuk menyerang layanan pihak lain. |
| BurpSuite_Pro | https://github.com/prash0xd/BurpSuite_Pro | Berpotensi cracked/piracy; gunakan Burp Suite resmi. |
| evilginx2 | https://github.com/kgretzky/evilginx2 | Phishing/MFA attack framework; awareness, defense training, atau lab legal only. |
| systemd-backdoor | https://github.com/MatheuZSecurity/systemd-backdoor/ | Backdoor/persistence-related; tidak cocok untuk toolkit operasional publik. |
| D3m0n1z3dShell | https://github.com/MatheuZSecurity/D3m0n1z3dShell | Shell/backdoor-style tooling; research-only. |
| Python-Backdoor | https://github.com/xp4xbox/Python-Backdoor | Backdoor tooling; tidak cocok untuk toolkit operasional publik. |
| Payload obfuscator | https://github.com/topics/payload-obfuscator | Obfuscation/evasion topic; simpan hanya untuk malware-analysis awareness. |
| Ransomware Database | https://github.com/topics/ransomware | Ransomware-related resources; hanya untuk defensive research di lab aman. |
| Malware Repository | https://github.com/topics/malware-samples | Malware sample-related resources; jangan jalankan di host utama. |
| intelligentexploit.com via HugeDomains | https://www.hugedomains.com/domain_profile.cfm?d=intelligentexploit.com | Domain profile/penjualan domain, bukan exploit database aktif. |

---

## 🧭 Safe Vulnerability Research Workflow

```text
1. Identify product / component / version
   ↓
2. Search CVE, NVD, vendor advisory, and package advisory
   ↓
3. Check KEV / EPSS / threat intelligence for exploitation context
   ↓
4. Check PoC references only for understanding and lab validation
   ↓
5. Verify affected versions and patch status
   ↓
6. Reproduce only in lab or authorized scope
   ↓
7. Document evidence, impact, affected asset, and mitigation
   ↓
8. Build detection, hardening, patch, or remediation recommendation
```

---

## 🔎 Safe Search Query Examples

```text
site:exploit-db.com Apache 2.4 CVE
site:packetstorm.news CVE-2024
site:github.com CVE-2025 PoC
site:nvd.nist.gov CVE product version
site:cisa.gov known exploited vulnerabilities product
site:msrc.microsoft.com CVE product
site:github.com/advisories package-name vulnerability
site:osv.dev package-name CVE
```

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

Jangan menggunakan exploit, PoC, payload, scanner, search engine, atau teknik dari resource ini untuk menyerang, mengeksploitasi, memindai, mengambil data, membuat persistence, melakukan credential theft, melakukan phishing, atau mengakses sistem pihak lain tanpa izin eksplisit.

Repository ini adalah katalog referensi untuk pembelajaran dan riset keamanan yang etis.
