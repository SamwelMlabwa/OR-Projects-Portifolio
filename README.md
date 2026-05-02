# Operational Research Projects Portfolio
### Samwel Osward Mlabwa
MSc Operational Research, University of Edinburgh (2025–2026)  
Mastercard Foundation Scholar  
📧 samwelmlabwa8@gmail.com | 🔗 [LinkedIn](your-linkedin-url)

---

## About
This repository contains reports and code from projects completed during my MSc in 
Operational Research at the University of Edinburgh. The projects cover mathematical 
optimisation, stochastic programming, simulation, and logistics network design — 
applied to real-world problems in urban mobility, energy systems, supply chain, 
and robotics.

---

## Projects

### 📁 [01 — Stochastic Bike Rebalancing Optimisation (Edinburgh)](./01_bike_rebalancing/)
**Methods:** Two-stage stochastic ILP, chance constraints, out-of-sample validation  
**Tools:** FICO Xpress, Python  
**Summary:** Formulated a stochastic optimisation model to minimise CO₂ emissions 
from Edinburgh's bike-share network under uncertain demand, jointly optimising 
initial fleet allocation and rebalancing decisions. Full rebalancing reduced car 
emissions by up to 33% versus no rebalancing. Value-of-perfect-information analysis 
confirmed that higher rebalancing capacity reduces exposure to forecast error.

---

### 📁 [02 — Laptop Manufacturing System Simulation](./02_laptop_manufacturing_simulation/)
**Methods:** Discrete-event simulation, statistical input analysis (MLE, AIC/BIC, 
K-S tests), Welch's procedure, batch means method  
**Tools:** Simul8, R  
**Summary:** Built a full discrete-event simulation of a laptop manufacturing 
process covering parallel production lines, inventory management, quality assurance, 
and boxing. Identified key bottlenecks and evaluated six improvement scenarios, 
achieving up to a 70.1% reduction in average cycle time through a combined 
inventory policy redesign.

---

### 📁 [03 — Strategic Logistics Network Design: Multi-Period MECWLP](./03_mecwlp_tartan_trade/)
**Methods:** MILP, two-stage stochastic programming, K-means clustering, 
attractiveness scoring  
**Tools:** FICO Xpress, Python  
**Summary:** Formulated and solved a Multi-Echelon Capacitated Warehouse Location 
Problem over a 10-year planning horizon for a Scottish distribution network 
(440 customers, 53 suppliers, 4 product groups). Extended to a two-stage stochastic 
formulation with 100 demand scenarios. The stochastic model (12 warehouses, 
£17.54M expected cost) substantially outperformed the deterministic solution 
(13 warehouses, £38.05M) with more cautious phased construction to hedge demand risk.

---

### 📁 [04 — Robot Recharging Infrastructure Design (Antarctica)](./04_robot_recharging_antarctica/)
**Methods:** MINLP, k-means construction heuristic, local search (geometric median 
relocation, robot re-allocation, station insertion), two-stage stochastic programming, 
Sample Average Approximation (SAA)  
**Tools:** FICO Xpress, Python  
**Summary:** Designed optimal recharging infrastructure for 1,072 battery-powered 
robots in Antarctica. Solved a full MINLP for small instances, then developed a 
heuristic pipeline achieving a 9.16% cost reduction (saving £131,593) on the full 
instance. Extended to stochastic SAA over 100 scenarios, achieving a 26.4% cost 
reduction (VSS = £292,954) versus the deterministic benchmark, generalising well 
out-of-sample.

---

### 📁 [05 — Power System Optimisation](./05_power_system_optimisation/)
**Methods:** Mathematical programming, network flow optimisation, 
stochastic energy modelling  
**Tools:** FICO Xpress, Python  
**Summary:** Applied optimisation techniques to power system planning problems 
including generation dispatch and network flow optimisation under uncertain 
renewable energy generation.

---

## Technical Skills
| Area | Tools & Methods |
|---|---|
| Optimisation Solvers | FICO Xpress, Gurobi |
| Programming | Python, R, C |
| Simulation | Simul8, Arena, Simio |
| Methods | LP, MIP, MINLP, Stochastic Programming, SAA, Heuristics |

---
*University of Edinburgh — School of Mathematics*
