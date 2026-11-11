<div align="center">

<img src="assets/hero.svg" alt="Ricardo Solís — cybersecurity engineering, detection, defense and research" width="100%" />

<br/>

<img src="assets/signal.gif" alt="Operational focus: detect the signal, verify the evidence, engineer the defense" width="100%" />

<br/>
<br/>

![Location](https://img.shields.io/badge/San_José-Costa_Rica-102333?style=flat-square&labelColor=133044&color=27566A)
[![Focus](https://img.shields.io/badge/Focus-Detection_Engineering-102333?style=flat-square&labelColor=133044&color=27566A)](#selected-work)
[![Opportunities](https://img.shields.io/badge/Open_to-SOC_%7C_Junior_Security_%7C_IT_Support-0D303A?style=flat-square&labelColor=133044&color=236B72)](#connect)

<a href="https://www.linkedin.com/in/ricardo-solis-arias-3a382628a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ricardo02solis@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-263B4D?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

### About me

I'm **José Ricardo Solís Arias**, a cybersecurity engineering student at **Universidad Fidélitas**, based in Costa Rica (expected graduation: **August 2027**). I focus on **security operations, detection engineering, and practical system defense**—from collecting host telemetry and writing detection rules to designing hardening tools with a way back when a change causes trouble.

I also bring hands-on computer repair and technical support experience across **Windows, Linux, and macOS**, along with a foundation in networking. My goal is to join a team where I can investigate real problems, document what I find, and build defenses that can be tested rather than simply trusted.

---

## Selected work

My repositories are built around a few recurring questions: **What can we observe? What can we prove? How do we make a change safely?**

<a href="https://github.com/RichSsa24/Sentinel_Linux2.0"><img src="assets/sentinel.svg" width="100%" alt="SENTINEL-LINUX 2.0 — Linux host intrusion detection" /></a>

**A Linux host-based intrusion detection system in asynchronous Python.** Collects authentication, process, file-integrity, and network activity; normalizes events and evaluates a declarative detection library mapped to MITRE ATT&CK.

- **Engineering evidence:** 17 detection rules, 15 ATT&CK techniques, automated tests, and an executable intrusion replay demo.
- **Architecture:** bounded ingestion pipeline, deduplication, persistence, authenticated FastAPI endpoints, Prometheus metrics, and Grafana dashboards.
- **Why it matters:** detections are only useful when their coverage, failure modes, and operational behavior can be inspected.

[**Explore the repository and demo →**](https://github.com/RichSsa24/Sentinel_Linux2.0) · [Detection coverage](https://github.com/RichSsa24/Sentinel_Linux2.0/blob/main/docs/COVERAGE.md) · [Threat model](https://github.com/RichSsa24/Sentinel_Linux2.0/blob/main/docs/THREAT_MODEL.md)

<br/>

<a href="https://github.com/RichSsa24/TORTUGA"><img src="assets/tortuga.svg" width="100%" alt="TORTUGA — reversible security hardening" /></a>

**A bilingual, cross-platform hardening CLI for Windows, Linux, and macOS.** It separates assessment from modification so users can understand the potential impact of a security change before applying it.

- **Safety-first workflow:** dry-run by default; changes require explicit application.
- **Change control:** preflight impact checks and per-run state records to support rollback.
- **Why it matters:** hardening should improve security without treating recoverability as an afterthought.

[**Explore the repository →**](https://github.com/RichSsa24/TORTUGA) · [Spanish documentation](https://github.com/RichSsa24/TORTUGA/blob/main/docs/README.es.md)

<br/>

<a href="https://github.com/RichSsa24/Cascabel"><img src="assets/cascabel.svg" width="100%" alt="CASCABEL — authorized adversary emulation and detection" /></a>

**An experimental purple-team platform connecting controlled emulation with detection development.** It uses signed authorization scopes, collects the resulting telemetry, and tests generated Sigma rules against observed evidence.

- **Authorization boundary:** Ed25519-signed scopes before test execution.
- **Detection workflow:** technique emulation → telemetry → Sigma rule synthesis → verification.
- **Why it matters:** a plausible detection rule is not the same thing as a validated one.

[**Explore the repository →**](https://github.com/RichSsa24/Cascabel)

<br/>

<a href="https://github.com/RichSsa24/quantum-feature-selection-nids"><img src="assets/quantum.svg" width="100%" alt="Quantum feature selection for network intrusion detection research" /></a>

**Applied research at the intersection of network intrusion detection and quantum optimization.** Formulates feature selection on the NSL-KDD dataset as QUBO, solves it with QAOA in Qiskit, and compares the results with classical feature-selection baselines.

- **Research focus:** reproducibility, mathematical formulation, and fair comparison against classical methods.
- **Scope:** simulator-scale experiment; **not a claim of quantum advantage**.

[**Read the experiment and results →**](https://github.com/RichSsa24/quantum-feature-selection-nids)

---

## Technical focus

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,bash,powershell,linux,docker,git,github,postgres,fastapi,prometheus,grafana,vscode&theme=dark&perline=12" alt="Python, Bash, PowerShell, Linux, Docker, Git, GitHub, PostgreSQL, FastAPI, Prometheus, Grafana and VS Code" />
</div>

| Area | Tools & methods |
|:--|:--|
| **Detection & analysis** | MITRE ATT&CK, log correlation, Snort, Wireshark, Nmap, host telemetry |
| **Systems & networks** | Linux, Windows, macOS, TCP/IP, Cisco networking, Bash, PowerShell |
| **Software & operations** | Python, FastAPI, PostgreSQL, Docker, Git, GitHub Actions, Prometheus, Grafana |
| **Security engineering** | Threat modeling, least privilege, security testing, configuration hardening, rollback design |
| **Research** | Qiskit, QAOA, QUBO / Ising, experimental benchmarking |

<details>
<summary><b>How I approach a security problem</b></summary>

1. **Establish visibility:** identify what the host, network, or application can actually tell us.
2. **Model the failure:** connect suspicious behavior to a concrete threat hypothesis or misconfiguration.
3. **Test the control:** use reproducible scenarios, meaningful negative tests, and documented limitations.
4. **Preserve recoverability:** make changes deliberate, traceable, and reversible whenever possible.
5. **Write it down:** leave clear evidence and operational documentation for the next person.

</details>

---

## Education & credentials

**B.Sc. in Cybersecurity Engineering** — Universidad Fidélitas, Costa Rica  
*In progress · Expected August 2027*

**Cisco:** CCNA · Linux Essentials · IT Essentials · Python Essentials  
**Quantum learning:** QWorld QBronze · QCobalt  
**Currently preparing:** ISC2 Certified in Cybersecurity (CC)

---

## Beyond the terminal

Outside of security engineering, I spend time on **powerlifting**, combat sports, and understanding new technical subjects from first principles. The same habits carry over into my work: consistency, curiosity, and testing assumptions.

---

## Connect

I'm interested in **SOC, junior cybersecurity, and technical support opportunities**, especially positions where investigation, systems knowledge, and engineering meet.

<div align="center">
  <a href="https://www.linkedin.com/in/ricardo-solis-arias-3a382628a/"><img src="https://img.shields.io/badge/LinkedIn-Professional_profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" /></a>
  <a href="mailto:ricardo02solis@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-1E3A4A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Ricardo" /></a>
  <a href="https://github.com/RichSsa24?tab=repositories"><img src="https://img.shields.io/badge/GitHub-View_all_projects-182A37?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" /></a>
</div>

<p align="center"><sub>Thanks for taking a look at my work.</sub></p>
