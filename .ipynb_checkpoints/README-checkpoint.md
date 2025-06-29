##  Food Delivery  Cost and Profitability Analysis

### 🧠Background
The food delivery industry has rapidly expanded, with numerous players competing on pricing, discounts, and service fees. Understanding the true cost and profitability per order is essential for sustaining operations and making data-driven strategic decisions.

### 💼 Business Problem
Food delivery services face challenges balancing delivery costs, processing fees, discounts, and commissions, often resulting in losses despite high order volumes. The key problem is identifying how to optimize pricing and promotional strategies to maximize profitability without sacrificing customer acquisition.

### 🛠️ Methods
- **Data Preparation**: Loaded and cleaned the dataset, converting date and time columns to datetime format for accurate temporal analysis.

- **Discount Extraction**: Implemented a regex-based function to automatically extract and standardize discount values from varied textual formats (percentage or fixed amounts).

- **Cost Calculation**: Computed total costs per order by combining delivery fees, payment processing fees, and calculated discount amounts.

- **Profit Analysis**: Calculated per-order profit by subtracting total costs from commission revenue, identifying profitable vs. loss-making orders.

- **Profitability Profiling**: Analyzed profitable orders to determine average commission and discount percentages that support profitability.

- **Scenario Simulation**: Modeled new pricing strategies by applying recommended commission and discount rates to the dataset, simulating potential profitability improvements.

- **Visualization**: Created informative charts including profit distributions, cost breakdowns, and comparative profit simulations to facilitate insight communication.

### 📊 Results
- The analysis revealed an overall negative profitability, with total costs—including delivery fees, payment processing fees, and discounts—exceeding commission revenues.

- Discounts were identified as a major contributor to the high cost structure, significantly impacting profit margins.

- Profitable orders typically featured an average commission rate of approximately 37% and a discount rate near 10%.

- Simulation of adjusted pricing strategies using a 30% commission and 6% discount demonstrated a notable shift toward higher profitability and fewer loss-making orders.

- Visualizations effectively highlighted the distribution of profits, cost components, and the positive impact of optimized pricing strategies.


### ✅ Conclusion / Summary of Findings

This analysis highlights that current discount practices heavily erode profitability, often resulting in losses despite steady commission revenues. By examining profitable orders, we identified key thresholds for commission and discount rates that sustain positive margins. The simulation of optimized pricing strategies demonstrates the potential to significantly improve overall profitability by balancing competitive discounts with sustainable commissions. These insights provide actionable guidance for food delivery services to refine their pricing models, control costs, and enhance long-term financial performance. The methodology also offers a repeatable framework for ongoing analysis and strategy adjustment.
