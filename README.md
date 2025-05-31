# 🧴 Ulta Beauty Waiting Line Dynamic Simulation
## 📍 Project Overview: 
- This project models the customer waiting line at a real Ulta Beauty store in Denton, TX.
- My team researched the current as-is state of Ulta's waiting line, noting instances of peak traffic or minimum traffic
- We collected data on customer interarrival and service times to create dynamic simulations and conduct a thorough what-if analysis 

## 💼 Business Context:
Ulta operates with a 2-server FCFS shared queue model. 
Peak traffic: Friday (12 pm and 5 pm) and Saturday (1 pm)
Minimum traffic: Tuesday (all day) and Sunday (all day)

## 🛠️ Tools Used
- Microsoft Excel (Simulation + What-if Analysis)
- Advanced Excel Functions and Data Visualizations (histograms)
- Probability Distributions (done manually in Excel)
- Microsoft PowerPoint and Word (reporting)

## 🔍 What We Did
- Collected real interarrival and service time data at 5 separate instances
- Simulated 3 scenarios: **base case**, **best case**, and **worst case**
- Modeled the following what-if scenarios:
  - base case with 3 servers
  - base case with 4 servers
  - peak traffic with 1 server
  - peak traffic with 3 servers
  - Slowest service rate observed with 2 servers
- Used our findings to make predictions and recommend improvements to the waiting line

## 📊 Key Findings from Simulations
| Scenario        | Avg Wait Time | Max Wait Time | Probability of Waiting |
|-----------------|---------------|----------------|-------------------------|
| Base Case       | 1.17 mins     | 6.40 mins      | 61%                     |
| Best Case       | 0.01 mins     | 1.84 mins      | 2%                      |
| Worst Case      | 266.47 mins   | 539.12 mins    | 99%                     |

## 🔍 Key Findings from What-if Analysis

| Scenario                          | Avg Wait Time | Max Wait Time | Key Insight |
|----------------------------------|----------------|----------------|-------------|
| Base Case (3 servers)            | ↓ ~30%         | ↓ ~2 mins      | Increased efficiency |
| Base Case (4 servers)            | Marginal change| Marginal change| very little improvement  |
| 1 Server at Peak Traffic         | Very high      | Extremely high | Extremely inefficient and unreasonable |
| 3 Servers at Peak Traffic        | ↓ 50%          | ↓ 50%          | Highly efficient |
| Slowest Server (Base Scenario)   | ↑ to 15 mins   | ↑ to 30 mins   | Extremely inefficient and unreasonable |

## 💡 Recommendations
- Introduce a third server only during peak hours
- Avoid fourth server — adds cost with little increase to efficiency
- Avoid understaffing at high traffic times
- Ensure proper training practices to prevent extremely slow service times (as much as possible)

## 👥 Team
- Tanya Elder
- Elizabeth Burns
- Maahum Sattar
- Yuliana Vazquez






