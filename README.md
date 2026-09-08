# System Dynamics Models — Arya Kia

**A curated public portfolio of System Dynamics models I have built or am currently developing across social systems, electricity, water, desalination, and energy policy.**

| | |
|---|---|
| **Repository type** | Public model portfolio |
| **Focus** | System Dynamics · simulation · policy analysis · energy · water · social systems |
| **Role** | Researcher and model developer |
| **Model files** | Maintained separately and shared selectively |
| **Public disclosure** | Research questions, model boundaries, horizons, major stocks/feedbacks, scenarios, and outputs—without unpublished equations or parameters |

---

## Portfolio overview

My modeling work focuses on systems where outcomes emerge from **feedback, accumulation, delay, nonlinearity, infrastructure lifetimes, institutional response, and policy adaptation**.

The purpose of this repository is to show the **problems I model and how I structure them**, not to publish raw working models, calibration files, confidential datasets, or unpublished model logic.

## Model portfolio

### 1. Chain of Happiness

**Domain:** social systems · cooperation · digital platforms  
**Status:** model built · presented at ISDC 2026

A System Dynamics research project examining how participation, helping behavior, resource availability, matching success, trust, and platform growth interact in a digital social-support system.

The model explores reinforcing and balancing feedback such as:

- successful help → trust / visibility → participation → more potential matches
- growth → congestion / unmatched requests → lower perceived usefulness → weaker participation
- resource availability ↔ matching success ↔ contribution incentives

The research was presented at the **2026 International System Dynamics Conference in Delft** and is connected to the development of the live Chain of Happiness platform.

**Project showcase:** https://github.com/Aryakia/chain-of-happiness-showcase  
**Live platform:** https://chainofhappiness.com

---

### 2. Blackout — *Chasing the Light*

**Working title:** *Chasing the Light: A System Dynamics Assessment of the Structural Drivers Behind Iran's Blackout Gap*  
**Domain:** electricity systems · reliability · energy policy  
**Historical calibration period:** **1985–2024**  
**Projection horizon:** through **2035**

Blackout studies the paradox of substantial installed generation capacity and energy resources coexisting with a widening electricity supply–demand gap and recurring blackouts in Iran.

Rather than treating shortages as a single-capacity problem, the model examines interconnected mechanisms involving:

- electricity demand and production
- available vs installed generation capacity
- reliability and the emerging blackout gap
- investment and capacity-expansion response
- tariffs, subsidies, and financial pressure
- fuel dependence and supply constraints
- regional imbalance
- political/policy response
- renewable-policy incentives

The working model endogenizes policy pressure around renewable deployment from system conditions such as emissions, reliability stress, and installed capacity. Scenario work considers policy levers including investment, tariff reform, demand management, and generation choices.

**Public boundary:** detailed calibration data, equations, coefficients, and unpublished scenario results remain private until deliberately released.

---

### 3. DWD — Distributed Water Desalination

**Domain:** water resilience · distributed infrastructure · solar-energy coupling  
**Geographic structure:** zonal North / Center / South analysis

DWD explores whether **distributed, often solar-powered desalination near demand centers** can improve water-system resilience compared with continued dependence on centralized supply expansion.

The model is structured around questions such as:

- When does distributed desalination become attractive?
- How do leakage and conveyance losses change the value of local supply?
- How does desalination interact with grid stress and solar availability?
- Can distributed supply reduce groundwater pressure?
- What policy, regulation, cost, or adoption barriers slow deployment?
- Under what conditions can decentralized supply avoid centralized investment lock-in?

Public-safe model outputs include concepts such as:

- installed distributed desalination capacity
- distributed water volume
- associated energy use
- PV / renewable capacity interaction
- levelized-cost comparisons
- adoption/share of distributed supply
- leakage exposure
- groundwater pressure
- resilience indicators
- regional suitability across North / Center / South zones

**Public boundary:** numerical coefficients, detailed cost assumptions, unpublished calibration, and working model files remain private.

---

### 4. Water Infrastructure Choices Under Climate and Population Stress

**Research title:** *Water Infrastructure Choices Under Climate and Population Stress: A Zonal Simulation Study of Iran*  
**Domain:** water infrastructure · climate adaptation · policy analysis  
**Simulation horizon:** **2015–2040**  
**Research output:** Winter Simulation Conference 2026

The model studies how infrastructure strategies perform when climate stress, population pressure, supply constraints, leakage, investment, construction delays, and policy response interact over time.

#### Geographic zones

- North / Northwest
- Central Inland
- Coastal South

#### Scenario design

The research compares business-as-usual with **nine combined climate/population scenarios** constructed from:

- low / medium / high population pathways
- normal / dry / severe climate conditions

#### Strategies compared

- leakage-first intervention
- centralized capacity expansion
- distributed/local desalination
- adaptive infrastructure portfolios

#### Evaluation metrics

- unmet water demand
- total system cost
- cost per effective cubic metre delivered
- resilience / recovery performance

The project uses simulation to compare not only infrastructure capacity but also the timing, effectiveness, and resilience consequences of alternative investment pathways.

---

### 5. Energy Policy Simulator for Iran — Planned Adaptation

**Domain:** energy policy · electricity · emissions · technology transition  
**Status:** planned / in development

A planned adaptation of the **Energy Policy Simulator (EPS)** framework to the Iranian energy system.

The objective is to create a transparent policy-analysis environment for testing combinations of policies affecting areas such as:

- electricity generation mix
- energy demand and efficiency
- renewable deployment
- fossil-fuel use
- emissions
- technology adoption
- energy security
- policy-package interactions

The emphasis will be on **policy combinations**, because the impact of one intervention can depend strongly on what other policies are implemented at the same time.

---

## How I use System Dynamics

### Feedback

I focus on reinforcing and balancing structures that can generate counterintuitive behavior—for example, capacity expansion that temporarily relieves a shortage but also stimulates demand or locks a system into expensive infrastructure pathways.

### Stocks and flows

Physical capacity, knowledge, water availability, infrastructure, installed generation, trust, participation, and other accumulations are treated explicitly rather than as static variables.

### Delays

Construction, policy implementation, learning, behavioral response, deterioration, and institutional adaptation can create significant delay between an intervention and its visible effect.

### Policy learning

The models are primarily tools for asking:

- Why does the system behave this way?
- Which feedbacks dominate under different conditions?
- Which policies are robust across scenarios?
- Where can an intervention create unintended consequences?

## Application areas

- electricity reliability and energy shortages
- water infrastructure and climate resilience
- distributed desalination
- energy-transition policy
- social-impact platforms and cooperation
- infrastructure investment
- policy design and sensitivity analysis

## Public/private boundary

This public portfolio intentionally excludes raw model files, unpublished equations, coefficients, calibration tables, proprietary or non-public datasets, credentials, private collaborator material, and internal research notes. Only research questions, public outputs, high-level model architecture, and deliberately released scope information are included.

## Author

**Arya Kia**  
PhD researcher in Energy Systems Engineering · System Dynamics · Energy & Water Policy
