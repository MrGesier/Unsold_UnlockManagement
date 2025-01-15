# Unsold_UnlockManagement
Software allowing to manage your unlocks/Unsold unlocks &amp; Liquidity


# Tokenomics Dashboard

This interactive Streamlit app allows users to simulate token unlock schedules, evaluate market depth, analyze ROI, and manage unsold tokens dynamically.

## Features

### Tokenomics Inputs
- Define **maximum token supply**, **initial token price**, and **simulation start offset**.
- Choose between **constant price** or **stochastic price modeling** (Black-Scholes).

### Bear Market Periods
- Define custom **bear market periods** with adjustable sell pressure coefficients.
- Visualize bear markets' impact on overflow and ROI.

### Vesting Schedule Editor
- Edit **vesting schedules** for categories like Pre-Seed, Treasury, and Marketing.
- Adjust unlock percentages, lock-up periods, and sell pressure triggers dynamically.

### Unsold Tokens Management
- Redistribute unsold tokens using **smoothing** or **discrete deposits**.
- Visualize redistribution effects on unlock schedules and overflow.

### Dynamic Market Depth
- Simulate evolving **market depth thresholds** with liquidity provisioning.
- Highlight **overflow conditions** when unlock values exceed market depth.

### Rewards Allocation
- Distribute rewards based on a **logistic curve** for dynamic token supply allocation.

### Visualization
- Interactive plots for:
  - **Token unlock schedules** across scenarios (lower, median, upper paths).
  - ROI evolution with bear markets and overflow.
  - Cumulative unlocks with dynamic market depth and unsold tokens.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Streamlit installed

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
