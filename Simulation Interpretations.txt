# Simulation Findings

This simulation modeled the Ulta Beauty store’s waiting line under three scenarios: base case, best case, and worst case. These scenarios were designed to reflect realistic variations in customer interarrival times and server efficiency, allowing us to estimate system performance under different operational conditions.

---

## Base Case Scenario
- **Interarrival time**: 1.22 minutes
- **Service rate**: 1.12 minutes
- **Probability of waiting**: 0.61
- **Average wait time**: 1.17 minutes
- **Maximum wait time**: 6.40 minutes
- **Probability of waiting more than 1 minute**: 0.39

The base case reflects a typical day using observed averages. While wait times are manageable, the 61% chance of waiting highlights a possible area for improvement in the future.

---

## Best Case Scenario
- **Interarrival time**: 2.0 minutes
- **Service rate**: 0.39 minutes
- **Probability of waiting**: 0.02
- **Average wait time**: 0.01 minutes
- **Maximum wait time**: 1.84 minutes
- **Probability of waiting more than 1 minute**: 0.003

This optimistic scenario assumes a slower customer arrival rate and highly efficient servers. Wait times are nearly nonexistent, showing that even small increases in service speed significantly enhance queue performance.

---

## Worst Case Scenario
- **Interarrival time**: 0.83 minutes
- **Service rate**: 2.24 minutes
- **Probability of waiting**: 0.99
- **Average wait time**: 266.47 minutes
- **Maximum wait time**: 539.12 minutes
- **Probability of waiting more than 20 minutes**: 0.97

This extreme case demonstrates how poor staffing and high customer volume can overwhelm the system. Nearly all customers wait, with unacceptable wait times that would severely impact customer satisfaction and store reputation. This situation should be avoided at all costs.

---

