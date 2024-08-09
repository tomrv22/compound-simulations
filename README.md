# Financial Planning Simulation
## Overview
This project provides comprehensive simulations for systematic investment plans (SIPs) and systematic withdrawal plans (SWPs). The aim is to help users understand how their investment corpus grows over time and estimate how long it will last during the withdrawal phase.

## Key Features
### Single Simulation
  Calculates fund longevity based on specific user inputs.

### Multiple Simulations
  Runs thousands of simulations (user inputted number) to provide a normal distribution of fund exhaustion years, offering a clearer picture.
  ![image](https://github.com/user-attachments/assets/b7def629-11f0-4ead-ada8-6546b5518601)

### Live Corpus Visualization
  Shows real-time changes in the corpus during the withdrawal phase.
  ![image](https://github.com/user-attachments/assets/f0be860f-7c6e-4600-b56b-efcfdc16802d)

### Comparison Analysis
  Compares the effectiveness of lump sum investing vs. monthly SIPs vs. yearly SIPs.
  
## Parameters Considered
**Initial Investment:** The starting amount invested.

**Monthly Contribution:** Regular monthly investment.

**Annual hike in monthly contribution:** The percentage increase in monthly contribution at the start of every year

**Annual Growth Rate:** Growth rate of the investment corpus, sampled from a normal distribution.

**Standard Deviation of Growth Rate:** Variability in the annual growth rate.

**Inflation Rate:** Rate at which the cost of living increases.

**Standard Deviation of Inflation Rate:** Variability in the inflation rate.

**Conservative Growth Rate:** Safe, steady growth rate after the investment period.

**Yearly Withdrawal:** Amount withdrawn annually during the withdrawal phase.

**Lifestyle Inflation:** Annual increase in withdrawal amount to maintain lifestyle.
