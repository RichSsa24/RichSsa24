
<!--
  RICARDO SOLÍS / GITHUB PROFILE
  Editorial security portfolio · zero local image assets
  Remote SVG endpoints: readme-typing-svg.demolab.com, shields.io, skillicons.dev
-->

<div align="center">

<sub>J O S É &nbsp; R I C A R D O &nbsp; S O L Í S &nbsp; A R I A S</sub>

<h1>Engineering security.<br>Proving it works.</h1>

<p><strong>Detection engineering &nbsp;·&nbsp; Secure systems &nbsp;·&nbsp; Applied research</strong></p>

<img
  src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&amp;weight=500&amp;size=16&amp;duration=3200&amp;pause=1250&amp;color=C5A572&amp;center=true&amp;vCenter=true&amp;width=760&amp;height=38&amp;lines=Observe+the+system.+Understand+the+threat.;Build+the+detection.+Verify+the+result.;Harden+with+care.+Keep+the+rollback."
  alt="Observe the system. Understand the threat. Build the detection. Verify the result. Harden with care. Keep the rollback."
/>

<p>
  <img src="https://img.shields.io/badge/BASED%20IN-SAN%20JOS%C3%89%2C%20CR-15191E?style=flat-square&amp;labelColor=15191E&amp;color=343B45" alt="Based in San José, Costa Rica" />
  &nbsp;
  <img src="https://img.shields.io/badge/FOCUS-SOC%20%2F%20BLUE%20TEAM-15191E?style=flat-square&amp;labelColor=15191E&amp;color=343B45" alt="Focus: SOC and Blue Team" />
  &nbsp;
  <img src="https://img.shields.io/badge/AVAILABILITY-OPEN%20TO%20JUNIOR%20ROLES-15191E?style=flat-square&amp;labelColor=15191E&amp;color=343B45" alt="Open to junior roles" />
</p>

<p>
  <a href="https://www.linkedin.com/in/ricardo-solis-arias-3a382628a/">LinkedIn</a>
  &nbsp; / &nbsp;
  <a href="mailto:ricardo02solis@gmail.com">Email</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/RichSsa24?tab=repositories">Repositories</a>
</p>

</div>

---

### THE SHORT VERSION

I'm a cybersecurity engineering student in Costa Rica, graduating in **August 2027**. My work sits at the intersection of **Linux security monitoring, detection engineering, reversible system hardening, and adversary emulation**.

I care about the unglamorous parts of security: threat models, observable behavior, failure modes, rollback paths, tests, and documentation someone else can actually operate. The projects below are where I put that into practice.

> **My approach:** If a security control cannot be explained, tested, and operated safely, it is not finished.

---

## 01 / Selected engineering

<table>
  <tr>
    <td width="22%" valign="top"><strong>01 — DETECT</strong><br><sub>FEATURED PROJECT</sub></td>
    <td valign="top">
      <h3><a href="https://github.com/RichSsa24/Sentinel_Linux2.0">SENTINEL-LINUX 2.0</a></h3>
      <strong>Host-based intrusion detection for Linux.</strong>
      <p>An asynchronous Python detection pipeline that collects SSH, process, file-integrity, and network telemetry; normalizes and deduplicates events; evaluates declarative rules mapped to MITRE ATT&amp;CK; and exposes evidence through an authenticated API and operational metrics.</p>
      <p><code>Python</code> <code>Linux</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Prometheus</code> <code>MITRE ATT&amp;CK</code></p>
      <p><a href="https://github.com/RichSsa24/Sentinel_Linux2.0#try-it-in-30-seconds"><strong>Run the demo →</strong></a> &nbsp;·&nbsp; <a href="https://github.com/RichSsa24/Sentinel_Linux2.0/blob/main/docs/COVERAGE.md">Detection coverage</a> &nbsp;·&nbsp; <a href="https://github.com/RichSsa24/Sentinel_Linux2.0/blob/main/docs/THREAT_MODEL.md">Threat model</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>02 — HARDEN</strong><br><sub>ENDPOINT SECURITY</sub></td>
    <td valign="top">
      <h3><a href="https://github.com/RichSsa24/TORTUGA">TORTUGA</a></h3>
      <strong>Cross-platform hardening with an exit strategy.</strong>
      <p>A bilingual CLI for Windows, Linux, and macOS. Changes are designed around dry-run defaults, preflight impact checks, configurable hardening levels, and per-run rollback instead of irreversible "security tweaks."</p>
      <p><code>Python</code> <code>Windows</code> <code>Linux</code> <code>macOS</code> <code>Rollback</code> <code>CLI</code></p>
      <p><a href="https://github.com/RichSsa24/TORTUGA"><strong>Explore project →</strong></a> &nbsp;·&nbsp; <a href="https://github.com/RichSsa24/TORTUGA/blob/main/docs/README.es.md">Documentación en español</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>03 — VALIDATE</strong><br><sub>PURPLE TEAM</sub></td>
    <td valign="top">
      <h3><a href="https://github.com/RichSsa24/Cascabel">CASCABEL</a></h3>
      <strong>Authorization-first adversary emulation and detection validation.</strong>
      <p>An experimental purple-team platform combining signed execution scopes, controlled attack-technique emulation, captured telemetry, and evidence-grounded Sigma rule generation. Built around the idea that a detection should be tested against observed behavior—not assumed to work.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>React</code> <code>Ed25519</code> <code>Sigma</code> <code>MITRE ATT&amp;CK</code></p>
      <p><a href="https://github.com/RichSsa24/Cascabel"><strong>Explore project →</strong></a></p>
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>04 — RESEARCH</strong><br><sub>QUANTUM / ML</sub></td>
    <td valign="top">
      <h3><a href="https://github.com/RichSsa24/quantum-feature-selection-nids">Quantum Feature Selection for NIDS</a></h3>
      <strong>QAOA applied to intrusion-detection feature selection.</strong>
      <p>A reproducible experiment that formulates feature selection on NSL-KDD as QUBO / Ising optimization, evaluates QAOA using Qiskit, and compares results with classical baselines. A research exercise—not a claim of quantum advantage.</p>
      <p><code>Python</code> <code>Qiskit</code> <code>QAOA</code> <code>QUBO</code> <code>Scikit-learn</code></p>
      <p><a href="https://github.com/RichSsa24/quantum-feature-selection-nids"><strong>Explore research →</strong></a></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>Inside the engineering: what I optimize for</strong></summary>

| Design question | How it shapes my work |
| :--- | :--- |
| **Can we trust the signal?** | Explicit event schemas, rule validation, positive and negative detection tests. |
| **What happens under load?** | Bounded queues, backpressure, idempotent writes, measurable performance. |
| **Can we undo the change?** | Dry-run defaults, impact checks, and recorded rollback state. |
| **What can go wrong?** | Threat modeling, least privilege, unsafe input handling, documented limitations. |
| **Can someone else run it?** | Reproducible demos, operations documentation, and clear failure behavior. |

The strongest design decision is often the one that makes a system **auditable, predictable, and maintainable**.

</details>

---

## 02 / A closer look: SENTINEL

The project most closely aligned with the work I want to do in a Security Operations Center.

<table>
  <tr>
    <td align="center"><strong>4</strong><br><sub>TELEMETRY COLLECTORS</sub></td>
    <td align="center"><strong>17</strong><br><sub>DETECTION RULES</sub></td>
    <td align="center"><strong>15</strong><br><sub>ATT&amp;CK TECHNIQUES</sub></td>
    <td align="center"><strong>910+</strong><br><sub>TESTS DOCUMENTED</sub></td>
  </tr>
</table>

```text
  LINUX HOST
      │
      ├── SSH authentication ─────┐
      ├── Process activity ───────┤
      ├── File integrity ─────────┤
      └── Network sockets ────────┘
                                  │
                          NORMALIZE / QUEUE
                                  │
                            DEDUPLICATION
                                  │
                         ATT&CK-MAPPED RULES
                                  │
                      ALERTS / STORAGE / API
                                  │
                        METRICS & OPERATIONS
```

A working security tool should come with evidence. SENTINEL's repository documents an executable intrusion demo, a detection coverage matrix, security design decisions, benchmarks, and automated quality gates. The numbers above reflect the repository documentation rather than live production measurements.

[**Inspect the architecture and implementation →**](https://github.com/RichSsa24/Sentinel_Linux2.0)

---

## 03 / Technical foundation

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,bash,powershell,linux,kali,windows,docker,fastapi,postgres,git,github,grafana,prometheus&amp;theme=dark&amp;perline=13" alt="Python, Bash, PowerShell, Linux, Kali, Windows, Docker, FastAPI, PostgreSQL, Git, GitHub, Grafana, Prometheus" />
</p>

| Domain | Tools and concepts |
| :--- | :--- |
| **Detection & security operations** | Host telemetry · Log analysis · MITRE ATT&amp;CK · Snort · Wireshark · Nmap |
| **Engineering** | Python · Bash · PowerShell · FastAPI · REST APIs · Git · CI workflows · Automated tests |
| **Systems & infrastructure** | Linux · Windows · macOS · Docker · PostgreSQL · Prometheus · Grafana |
| **Networking** | TCP/IP · Routing & switching · VLANs · ACLs · Network troubleshooting |
| **Security methodology** | Threat modeling · Least privilege · Hardening · Incident investigation fundamentals · NIST CSF · CIS Controls |
| **Research** | Qiskit · QAOA · QUBO / Ising models · Reproducible experiments |

My strongest practical focus is **Linux-based detection tooling and Python security engineering**. I also have hands-on experience troubleshooting and repairing computers across Windows, macOS, and Linux.

---

## 04 / Background & credentials

<table>
  <tr>
    <td width="25%"><strong>EDUCATION</strong></td>
    <td><strong>B.Eng. in Cybersecurity</strong><br>Universidad Fidélitas · Costa Rica<br><sub>Expected completion: August 2027</sub></td>
  </tr>
  <tr>
    <td><strong>EXPERIENCE</strong></td>
    <td>Hands-on computer repair and cross-platform technical support (since 2025). Previous bilingual customer service experience (2024).</td>
  </tr>
  <tr>
    <td><strong>CREDENTIALS</strong></td>
    <td>Cisco CCNA · Linux Essentials · IT Essentials · Python Essentials</td>
  </tr>
  <tr>
    <td><strong>IN PROGRESS</strong></td>
    <td>ISC2 Certified in Cybersecurity (CC)</td>
  </tr>
</table>

I am targeting **SOC Analyst I, Junior Security Analyst, and IT Support** opportunities where I can contribute from day one while developing deeper incident-response and detection-engineering skills.

---

## 05 / Beyond the terminal

Outside security engineering, I'm usually training **powerlifting and combat sports**, reading, or experimenting with a new systems concept. The same habits carry over: learn the fundamentals, measure progress, and respect the details.

---

<div align="center">

<sub>HAVE A SYSTEM TO SECURE, A DETECTION TO BUILD, OR A PROBLEM WORTH EXPLORING?</sub>

<h2>Let's work on something that holds up under scrutiny.</h2>

<p>
  <a href="https://www.linkedin.com/in/ricardo-solis-arias-3a382628a/">
    <img src="https://img.shields.io/badge/CONNECT-LINKEDIN-806038?style=for-the-badge&amp;labelColor=15191E&amp;logo=linkedin&amp;logoColor=C5A572" alt="Connect on LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:ricardo02solis@gmail.com">
    <img src="https://img.shields.io/badge/CONTACT-EMAIL-806038?style=for-the-badge&amp;labelColor=15191E&amp;logo=gmail&amp;logoColor=C5A572" alt="Contact by email" />
  </a>
</p>

<sub>DESIGNED WITH RESTRAINT. BUILT AROUND EVIDENCE.</sub>

</div>

