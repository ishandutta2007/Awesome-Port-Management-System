# Awesome-Port-Management-System

## Top Port Management System Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Terminal Operating Systems (TOS), Port Operations, Yard & Vessel Planning, Gate Management & Maritime Logistics*  
**Last updated: September 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Port Management Systems** and **Terminal Operating Systems (TOS)**. These systems manage container and cargo movements, vessel and yard planning, gate operations, equipment control, and overall terminal efficiency in ports and intermodal facilities.

**Examples** include NAVIS N4 (Kaleris), Tideworks, TOS+, PortX, PortPro, CargoSmart, Awake.AI, Portchain, Cargomatic Port, and related Kaleris offerings (the category leaders).

**Open-source emphasis**: Production-grade, full-featured open-source Terminal Operating Systems comparable to commercial TOS platforms are extremely limited. Most available projects are educational prototypes, vessel-focused maritime systems, or supporting tools for data, planning, or general logistics. This section lists every significant relevant project found and notes the reality of the domain.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description & Key Capabilities | Specific Pricing / Starting Tier | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[NAVIS N4 / Octopi](https://kaleris.com/)** (Kaleris) | Enterprise terminal operating system (N4) and cloud-native TOS (Octopi) for vessel planning, container yard management, equipment control, gate automation, and rail operations. | Starting at **$2,500/month** (Octopi cloud subscription) or **$50,000/year** base tier (N4 enterprise deployment). | No free forever tier; **30-day proof-of-concept / guided sandbox trial** upon sales qualification with pre-loaded terminal test datasets. |
| **[Tideworks Mainsail](https://tideworks.com/)** | Full-scale marine and intermodal Terminal Operating System offering real-time vessel planning, yard inventory tracking, gate automation, and rail interchange management. | Starting at **$4,000/month** (hosted SaaS tier) or **$45,000/year** base enterprise license based on annual TEU throughput. | No free forever tier; **14-day interactive sandbox trial** during technical evaluation with up to 5 concurrent user seats and simulated terminal events. |
| **[CARGOES TOS+](https://www.dpworld.com/)** (DP World) | Cloud-based Terminal Operating System designed for general cargo, bulk, and container terminals featuring automated gate appointments, berth planning, and equipment dispatch. | Starting at **$3,000/month** base subscription tier for regional and medium-sized terminal facilities. | No free forever tier; **14-day pilot sandbox trial** available on demo request with up to 10 simulated vessel calls and yard allocations. |
| **[PortPro](https://portpro.io/)** | Port drayage TMS and logistics operating platform connecting carriers, brokers, and marine terminals with automated dispatch, GPS geofencing, and driver workflow tracking. | Starting at **$150/month per active driver** (includes unlimited back-office dispatch and billing user seats). | No free forever tier; **14-day live pilot trial** for verified carriers and brokers with full access to driver mobile apps and real-time port tracking. |
| **[CargoSmart / IQAX](https://www.cargosmart.com/)** | Ocean shipping visibility and port management platform providing real-time container milestone tracking, predictive ETA analytics, and electronic document exchange. | Starting at **$299/month** (CargoSmart Professional tier) or **$99/month** base package on CargoSmart Fleet IO. | **Free forever tier** with tracking for up to 5 active ocean shipments/month; **30-day trial** for Professional tier with up to 100 tracked Bills of Lading. |
| **[Awake.AI](https://www.awake.ai/)** | AI-driven Smart Port as a Service platform providing predictive vessel arrival (Just-In-Time), berth planning, turnaround timestamps, and port area emissions tracking. | Starting at **€490/month** (~$530/month) for Smart Port starter tier targeting single-berth operators and port authorities. | **Free forever plan** supporting basic port call timestamps for up to 20 vessel calls/month; **30-day trial** with full predictive AI modules and API access. |
| **[Portchain](https://www.portchain.com/)** | Collaborative berth planning and scheduling software facilitating Just-In-Time (JIT) vessel arrivals and berth alignment between container terminals and ocean carriers. | Starting at **$1,500/month** for container terminals with single-berth operational scope. | **Free forever tier** for ocean carriers submitting vessel schedules; **30-day pilot trial** for container terminals with up to 50 scheduled vessel calls. |
| **[Cargomatic Port](https://www.cargomatic.com/)** | Intermodal drayage and port staging coordination software providing terminal in-gate status, off-dock container recovery, and automated drayage routing. | Starting at **$500/month** base platform subscription + **$25 per executed drayage container dispatch**. | No free forever tier; **14-day sandbox trial** for shippers and logistics service providers with up to 10 simulated container recovery moves. |
| **[Portcast](https://portcast.io/)** | Real-time container tracking, port congestion analytics, dynamic ETA predictions, and demurrage & detention avoidance software. | Starting at **$500/month** (Starter tier for up to 500 tracked containers/month). | No free forever tier; **30-day free trial** with access to the KPI analytics dashboard and tracking for up to 50 live containers. |
| **[Sinay Maritime](https://sinay.ai/)** | Port operational intelligence and environmental monitoring platform offering real-time port congestion indexes, air/water quality metrics, and maritime APIs. | Starting at **€199/month** (~$215/month) for Developer API Pro tier (up to 10,000 monthly API calls). | **Free forever plan** with up to 500 API calls/month for ETA, Carbon Footprint, and Port Congestion APIs. |
| **[CyberLogitec OPUS](https://www.cyberlogitec.com/)** | Enterprise container and multipurpose terminal operating system with advanced 3D yard visualization, intelligent crane dispatch, and automated gate processing. | Starting at **$3,500/month** (cloud-hosted regional tier) or **$60,000/year** standard enterprise on-premise license. | No free forever tier; **30-day supervised staging environment trial** available for qualified port authorities and terminal operators. |
| **[INFORM Syncrotess](https://www.inform-software.com/)** | Modular AI optimization software suite for container and bulk terminals, optimizing automated stacking cranes (ASC), straddle carriers, and gate appointment flow. | Starting at **$2,800/month** for single-module optimization add-on (e.g., Crane Optimizer or Gate Scheduler). | No free forever tier; **30-day proof-of-concept simulation trial** using historical yard and gate dataset logs. |
| **[TBA Group CommTrac / Autostore](https://tbagroup.com/)** | Specialized Terminal Operating System for bulk, breakbulk, and container terminals managing terminal inventory, rail links, vessel planning, and billing. | Starting at **$3,200/month** base software subscription for bulk/multipurpose facilities. | No free forever tier; **30-day guided evaluation trial** in a simulated terminal environment with preconfigured bulk/breakbulk cargo models. |

## Open-Source GitHub Projects

- **[Educational & prototype Port Managers](https://github.com/CirXe0N/PortManager)**  
  Simple open-source examples and academic projects modeling basic ship, dock, and cargo management for learning purposes. Not production TOS systems.

- **[Hackerfleet / HFOS](https://github.com/Hackerfleet/hfos)**  
  Open-source maritime modular system focused on vessel board computers, geo-information, and collaborative maritime tooling rather than commercial terminal operations.

- **[Maritime data & vessel tools](https://github.com/search?q=maritime+OR+port+OR+terminal+operating+OR+TOS)**  
  Community projects covering AIS data, vessel tracking, weather/tide information, NMEA handling, and related maritime software components.

- **[Open Ships and NMEA-focused projects](https://openships.ai/)**  
  Open-source maritime software oriented toward vessel networks, data flows, and onboard systems rather than full terminal operating systems.

- **[General logistics & yard prototypes](https://github.com/search?q=yard+management+OR+container+terminal+OR+port+management)**  
  Experimental or research-oriented codebases exploring container tracking, simple yard models, or port simulation.

- **[Simulation & optimization libraries](https://github.com/search?q=container+terminal+simulation+OR+port+optimization)**  
  Academic and open-source tools for simulating terminal operations, berth allocation, or yard strategies that can support research and planning.

### Additional Strong Open-Source Options

- **AIS & vessel tracking stacks**: Libraries and platforms for processing Automatic Identification System data.
- **GIS & mapping tools**: QGIS, PostGIS, and web mapping stacks used for port spatial data and visualization.
- **Event-driven & messaging systems**: Kafka, NATS, or MQTT-based architectures that can underpin custom port data platforms.
- **Optimization solvers**: Open-source mathematical programming tools applied to berth, crane, or yard optimization problems.
- **ERP & logistics modules**: Broader open-source ERP systems (e.g., ERPNext, Odoo) that some smaller facilities adapt for basic cargo and resource tracking.
- Research papers and reference implementations of terminal algorithms (often not production-ready software).

**Frameworks for building custom systems**:  
There is currently no widely adopted, production-ready open-source Terminal Operating System that can replace commercial platforms such as NAVIS N4 or Tideworks for medium-to-large container terminals.  
Commercial TOS solutions dominate because of the extreme operational complexity, safety requirements, equipment integrations, real-time performance needs, and long implementation cycles involved.  
Open-source components can support specific layers (data integration, visualization, simulation, optimization research, or vessel-side systems) and may be useful for smaller facilities, prototypes, or academic work.  
Any custom or hybrid approach requires deep domain expertise, rigorous testing, and careful attention to safety and reliability.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Port and terminal systems are safety- and mission-critical. They control physical equipment, vessel movements, and high-value cargo. Any software used in live operations must meet stringent reliability, security, and operational standards.
- Open-source projects listed here are primarily educational, research-oriented, or vessel-focused. They are not drop-in replacements for commercial Terminal Operating Systems. Deploying unproven software in live terminal environments carries significant operational and safety risk.

---

**Made for port operators, terminal managers, maritime technologists, and logistics innovators.**  
Let's encourage greater openness, interoperability, and research collaboration in port and terminal technology where feasible.
