<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b3d5c,100:00d9ff&height=200&section=header&text=Chafiq%20Boulghallat&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Cybersecurity%20Engineer%20%E2%80%A2%20Blue%20Team%20%E2%80%A2%20DevSecOps&descSize=16&descAlignY=58&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/chafiq753">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=00D9FF&center=true&vCenter=true&width=640&lines=Detecting+threats+before+they+become+incidents;SOC+%E2%80%A2+SIEM+%E2%80%A2+SOAR+%E2%80%A2+Incident+Response;Shifting+security+left+with+IaC+scanning;Author+of+iac-guard+%E2%80%94+pip+install+iacguard-cli" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/boulghallat-chafiq-565844335"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:cboulghallat@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00D9FF"/></a>
  <a href="https://pypi.org/project/iacguard-cli/"><img src="https://img.shields.io/badge/PyPI-iacguard--cli-0d1117?style=for-the-badge&logo=pypi&logoColor=00D9FF"/></a>
  <img src="https://komarev.com/ghpvc/?username=chafiq753&style=for-the-badge&color=00d9ff&label=PROFILE+VIEWS"/>
</p>

---

### `> whoami`

```yaml
name:      Chafiq Boulghallat
role:      Cybersecurity Engineer — Blue Team
school:    ENSA Béni Mellal · AI & Cybersecurity Engineering (5th year)
based_in:  Morocco 🇲🇦
focus:     [threat detection, SOC automation, incident response, DevSecOps]
building:  iac-guard — open-source IaC security & compliance scanner
open_to:   PFE internship · SOC / Detection Engineering / DevSecOps
```

---

### 🛡️ Featured work

<table>
<tr>
<td width="50%" valign="top">

#### [iac-guard](https://github.com/chafiq753/iac-guard)
Open-source IaC security scanner that runs **Gitleaks, Checkov and Semgrep** in one pass, scores the result and blocks risky commits in CI. Available as CLI, Docker image and GitHub Action.

<p>
<img src="https://img.shields.io/pypi/v/iacguard-cli?style=flat-square&color=00d9ff&label=pypi"/>
<img src="https://img.shields.io/github/v/release/chafiq753/iac-guard?style=flat-square&color=00d9ff"/>
<img src="https://img.shields.io/badge/GitHub-Marketplace-0d1117?style=flat-square&logo=github"/>
<img src="https://img.shields.io/github/license/chafiq753/iac-guard?style=flat-square&color=555"/>
</p>

```bash
pip install "iacguard-cli[scanners]"
iacguard scan .
```

</td>
<td width="50%" valign="top">

#### SOAR Pipeline — automated detection & response
**Suricata + Wazuh + n8n + OPNsense.** Alerts are enriched in parallel (AbuseIPDB, VirusTotal, GeoIP), scored by a weighted engine, then the attacker IP is **blocked automatically** on the firewall.

```
Suricata/Wazuh ─► n8n ─► CTI enrichment
                         └► threat score ─► OPNsense block
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### LaYura — SOC platform
Full-stack SOC: Python monitoring agent, FastAPI + PostgreSQL backend, React dashboard, **IsolationForest anomaly detection**, AbuseIPDB threat intel, Trivy container scanning and an **LLM-powered AI analyst**.

</td>
<td width="50%" valign="top">

#### Detection engineering
Custom Wazuh rules (SSH brute-force, sudo abuse, FIM, `curl | bash`), Suricata ET ruleset tuning, attack simulation from Kali (nmap, nikto, sqlmap, Slowloris) to validate every detection.

</td>
</tr>
</table>

---

### 🧰 Arsenal

**Blue Team & Security**
<p>
<img src="https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=wazuh&logoColor=white"/>
<img src="https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square"/>
<img src="https://img.shields.io/badge/Zeek-0d1117?style=flat-square"/>
<img src="https://img.shields.io/badge/n8n_(SOAR)-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
<img src="https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white"/>
<img src="https://img.shields.io/badge/Checkov-7B42BC?style=flat-square"/>
<img src="https://img.shields.io/badge/Gitleaks-0d1117?style=flat-square"/>
<img src="https://img.shields.io/badge/Semgrep-0d1117?style=flat-square&logo=semgrep&logoColor=white"/>
<img src="https://img.shields.io/badge/OPA-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white"/>
<img src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white"/>
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white"/>
</p>

**Dev & Infra**
<p>
<img src="https://skillicons.dev/icons?i=python,fastapi,react,nextjs,tailwind,postgres,docker,terraform,githubactions,linux,ubuntu,git&theme=dark" />
</p>

**Frameworks & Compliance:** ISO 27001 · NIST · CIS Benchmarks · MITRE ATT&CK · RGPD · Loi 09-08 (CNDP)

---

### 📊 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=chafiq753&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9"/>
  <img height="165" src="https://streak-stats.demolab.com?user=chafiq753&hide_border=true&background=0d1117&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff&sideLabels=c9d1d9&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff"/>
</p>

<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=chafiq753&bg_color=0d1117&color=c9d1d9&line=00d9ff&point=ffffff&area=true&area_color=00d9ff&hide_border=true"/>
</p>

---

<p align="center">
  <i>"Defense is a process, not a product."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,50:0b3d5c,100:0d1117&height=110&section=footer" width="100%"/>
</p>
