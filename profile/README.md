 <div align="center">

<!-- HERO -->

<p>
  <img src="./assets/temple-hero.jpg" width="100%" alt="Temple Labs futuristic engineering environment"/>
</p>

# TEMPLE LABS

### FORGE / ADVANCING HUMANITY.

**WE DON'T JUST BUILD SOFTWARE.**
<br/>
**WE EXPLORE WHAT SOFTWARE CAN BECOME.**

<br/>

<a href="#projects">PROJECTS</a> &nbsp; ◈ &nbsp;
<a href="#disciplines">DISCIPLINES</a> &nbsp; ◈ &nbsp;
<a href="#architecture">ARCHITECTURE</a> &nbsp; ◈ &nbsp;
<a href="#research">RESEARCH</a> &nbsp; ◈ &nbsp;
<a href="#connect">CONNECT</a>

</div>

---

<a id="mission"></a>

## ◈ 00 / THE MISSION

Temple Labs is an independent software engineering and technology research laboratory.

We design, engineer and explore intelligent systems, computational infrastructure and digital products.

Our work moves across disciplines. From artificial intelligence and distributed computing to cybersecurity, connected devices and experimental computing architectures.

We are not committed to a particular technology.

**We are committed to discovering better ways to solve problems.**

---

<a id="projects"></a>

# ⬡ 01 / PROJECT COMMAND CENTRE

<sub>SELECTED SYSTEMS · ENGINEERING · EXPERIMENTATION</sub>

Explore the projects. Each dossier expands to reveal its purpose and engineering direction.

<table>
<tr>
<td width="33%" align="center" valign="top">

<img src="./assets/jarkata.PNG" width="140" alt="Jarkata logo"/>

### JARKATA

**DIGITAL IDENTITY INTELLIGENCE**

Real-time video-call impersonation detection for a world where seeing is no longer believing.

`AI` `WebRTC` `Computer Vision`

<a href="#jarkata">OPEN PROJECT DOSSIER ↗</a>

</td>
<td width="33%" align="center" valign="top">

<img src="./assets/nfm26.jpg" width="140" alt="NFM26 logo"/>

### NFM26

**FOOTBALL SIMULATION**

A Nigerian football management universe combining tactical systems, player progression and match simulation.

`Simulation` `Game Systems` `AI`

<a href="#nfm26">OPEN PROJECT DOSSIER ↗</a>

</td>
<td width="33%" align="center" valign="top">

<img src="./assets/proton-x.png" width="140" alt="Proton-X logo"/>

### PROTON-X

**ALTERNATIVE COMPUTING RESEARCH**

An experimental computing concept investigating proton-based information transport as an alternative to conventional electron-based approaches.

`Physics` `Electronics` `Research`

<a href="#proton-x">OPEN RESEARCH DOSSIER ↗</a>

</td>
</tr>
</table>

### SYSTEM DOSSIERS

<details id="jarkata">
<summary><b>JARKATA / 001 — IDENTITY INTELLIGENCE</b></summary>

<div align="center">
<img src="./assets/jarkata.PNG" width="180" alt="Jarkata"/>
</div>

**Mission**

Explore how digital identity can be verified in real time during video communication.

**Problem space**

Video-call impersonation, synthetic identities and identity-based social engineering.

**Engineering domains**

- Browser-based media processing
- Real-time video analysis
- WebRTC integrations
- AI-assisted identity detection
- Enterprise security integrations

**Target environments:** Recruitment, enterprise IT and online interactions.

</details>

<details id="nfm26">
<summary><b>NFM26 / 002 — SPORTS SIMULATION</b></summary>

<div align="center">
<img src="./assets/nfm26.jpg" width="180" alt="NFM26"/>
</div>

**Mission**

Build a rich football management simulation rooted in Nigerian football culture.

**Systems**

- Tactical formations and match engines
- Player development and attributes
- Club management and competition systems
- 2D match simulation
- Dynamic football narratives
- Multilingual player experiences

**Engineering domains:** Simulation engineering, game systems, data modelling and interactive software.

</details>

<details id="proton-x">
<summary><b>PROTON-X / 003 — ALTERNATIVE COMPUTING RESEARCH</b></summary>

<div align="center">
<img src="./assets/proton-x.png" width="220" alt="Proton-X"/>
</div>

**Mission**

Investigate alternative physical mechanisms for information transport and computation, with particular interest in proton-based systems.

Conventional electronic computing relies on the movement and control of electrons. Proton-X explores a different possibility: whether proton transport and manipulation could provide a foundation for alternative computational architectures.

**Research dimensions**

1. **Proton transport:** Investigating mechanisms through which protons could be moved and controlled within suitable materials.
2. **Information representation:** Exploring how proton states, movement or distributions might encode information.
3. **Computational operations:** Investigating whether controllable proton dynamics could support logic operations and information processing.
4. **Materials science:** Studying proton-conducting materials, interfaces and physical constraints.
5. **Energy and efficiency:** Examining switching energy, speed, stability and practical operating conditions.
6. **Architecture:** Exploring how proton-based mechanisms might interact with conventional electronic systems.

**Research questions**

- Can proton transport be controlled with sufficient precision for computational applications?
- What physical structures could support reliable information representation?
- Could proton-based mechanisms complement conventional semiconductor technologies?
- What fundamental limitations would prevent practical implementation?

**Research classification**

`Computational Physics` · `Electronics` · `Materials Science` · `Alternative Computing`

<sub>Proton-X is an experimental research concept. Its proposed computational mechanisms remain subject to theoretical and experimental validation.</sub>

</details>

---

<a id="disciplines"></a>

# ⬡ 02 / ENGINEERING DISCIPLINES

<details open>
<summary><b>01 — ARTIFICIAL INTELLIGENCE</b></summary>

Intelligent agents, applied machine learning, LLM orchestration, computer vision and autonomous workflows.

</details>

<details>
<summary><b>02 — DISTRIBUTED COMPUTING</b></summary>

Distributed services, messaging infrastructure, event-driven architecture, concurrency and real-time processing.

</details>

<details>
<summary><b>03 — CLOUD & INFRASTRUCTURE</b></summary>

Cloud-native systems, container orchestration, deployment automation, observability and production reliability.

</details>

<details>
<summary><b>04 — SECURITY & DIGITAL TRUST</b></summary>

Identity verification, secure application architecture, privacy-aware systems and threat intelligence.

</details>

<details>
<summary><b>05 — BLOCKCHAIN & WEB3</b></summary>

Smart contracts, decentralized applications, wallet infrastructure and blockchain integrations.

</details>

<details>
<summary><b>06 — CONNECTED SYSTEMS & IOT</b></summary>

Sensors, telemetry, device communication, edge computing and intelligent automation.

</details>

---

<a id="architecture"></a>

# ⬡ 03 / SYSTEM ARCHITECTURE

**How we think about building systems.**

```mermaid
flowchart TB
    U["USER / EXTERNAL SYSTEMS"]
    A["APPLICATIONS & INTERFACES"]
    B["INTELLIGENCE & ORCHESTRATION"]
    C["CORE SERVICES & APIs"]
    D["DATA & EVENT INFRASTRUCTURE"]
    E["CLOUD / EDGE / COMPUTE"]

    U <--> A
    A <--> B
    B <--> C
    C <--> D
    D <--> E

    E -.-> M["OBSERVABILITY & TELEMETRY"]
    M -.-> C

    classDef primary fill:#071B11,stroke:#16C784,color:#E4FFF1
    classDef infra fill:#101820,stroke:#2489B5,color:#E1F4FF

    class U,A,B,C primary
    class D,E,M infra
```

<details>
<summary><b>EXPLORE THE ARCHITECTURAL LAYERS</b></summary>

| Layer | Responsibility |
|---|---|
| Interface | User interaction and external integrations |
| Intelligence | AI, decision-making and orchestration |
| Core services | Business logic and application capabilities |
| Data infrastructure | Persistence, messaging and event processing |
| Compute | Cloud, edge and deployment infrastructure |
| Observability | Monitoring, tracing, metrics and diagnostics |

This is a conceptual reference architecture. Individual systems use architectures appropriate to their requirements.

</details>

---

<a id="research"></a>

# ⬡ 04 / RESEARCH FRONTIER

**Questions worth investigating.**

| Research area | Exploration |
|---|---|
| Alternative computing | Proton-based computational mechanisms |
| Intelligent systems | Reliable autonomous agents |
| Digital trust | Real-time identity intelligence |
| Distributed systems | Resilient computational infrastructure |
| Materials and electronics | Physical mechanisms for information transport |
| Human-machine interfaces | More natural intelligent interactions |
| Connected environments | Software interacting with physical infrastructure |

<details>
<summary><b>OUR RESEARCH PHILOSOPHY</b></summary>

We distinguish between:

- **Established engineering:** Systems that can be implemented and validated.
- **Experimental engineering:** Approaches under active investigation.
- **Conceptual research:** Ideas requiring further theoretical and practical validation.

An interesting hypothesis is not an engineering achievement until evidence supports it.

</details>

---

<a id="technology"></a>

# ⬡ 05 / TECHNOLOGY MATRIX

<details open>
<summary><b>LANGUAGES & RUNTIMES</b></summary>

`Go` · `TypeScript` · `JavaScript` · `Python` · `Rust` · `C#`

</details>

<details>
<summary><b>APPLICATION ENGINEERING</b></summary>

`React` · `Next.js` · `Node.js` · `NestJS` · `React Native` · `.NET` · `Rails`

</details>

<details>
<summary><b>DATA & MESSAGING</b></summary>

`PostgreSQL` · `MongoDB` · `Redis` · `NATS` · `Kafka`

</details>

<details>
<summary><b>INFRASTRUCTURE</b></summary>

`AWS` · `Docker` · `Kubernetes` · `Terraform` · `Linux` · `OpenTelemetry`

</details>

<details>
<summary><b>REAL-TIME SYSTEMS</b></summary>

`WebSockets` · `WebRTC` · `WebTransport` · `REST APIs` · `Event-Driven Architecture`

</details>

---

<a id="connect"></a>

# ⬡ 06 / OPEN THE LAB

We welcome engineers, researchers, founders, designers and open-source contributors who are interested in building meaningful technology.

**Areas of collaboration**

- Open-source engineering
- Applied AI research
- Distributed infrastructure
- Experimental computing
- Product development
- Systems architecture
- Electronics and computational research

<br/>

<div align="center">

### HAVE AN INTERESTING PROBLEM?

**LET'S ENGINEER THE ANSWER.**

<br/>

<a href="https://github.com/tlabsxten?tab=repositories">
<img src="https://img.shields.io/badge/EXPLORE_REPOSITORIES-16C784?style=for-the-badge&logo=github&logoColor=black" alt="Explore repositories"/>
</a>

<a href="https://github.com/tlabsxten">
<img src="https://img.shields.io/badge/ENTER_THE_LAB-111111?style=for-the-badge&logo=github&logoColor=white" alt="Enter the lab"/>
</a>

<br/><br/>

---

# TEMPLE LABS

### FORGE / ADVANCING HUMANITY.

<sub>INNOVATE · ENGINEER · DEPLOY · EVOLVE</sub>

</div>
