# 📊 **Make vs Buy Cost Analysis in Supply Chain**

## 📘 Project Overview

This project focuses on evaluating supply chain procurement decisions by analyzing the "Make vs Buy" trade-off for various components. Using Power BI dashboards, the analysis integrates cost metrics including unit costs, non-recurring expenses, and capital investment needs to identify the most cost-effective sourcing option at varying production volumes.

## 🎯 Objectives

* Understand the cost structure of the "Buy" option by analyzing quotes from multiple suppliers.
* Create scenario-based visualizations to assess how costs evolve with production volume.
* Evaluate the "Make" option by including internal manufacturing costs and investment requirements.
* Recommend optimal sourcing strategies based on full cost comparison.
* Develop an interactive Power BI dashboard for dynamic decision-making support.

## 🛠️ Tools & Technologies

| Tool / Language                 | Purpose                                       |
| ------------------------------- | --------------------------------------------- |
| Microsoft Power BI              | Data visualization and interactive dashboards |
| Excel                           | Source data handling and basic preprocessing  |
| DAX (Data Analysis Expressions) | Measures and calculated columns for Power BI  |
| Power Query                     | Data transformation within Power BI           |

## 📈 Key Components

### 1. **Buy Option Analysis**

* Visual breakdown of **unit cost**, **non-recurring expenses**, and **full cost** for each supplier.
* Interactive filtering by **part number** and **volume levels** (e.g., 1,000, 5,000, 10,000).
* Identification of the lowest cost supplier (e.g., *Widgetmakers, Inc.*).

### 2. **Scenario Planning Tool**

* Adjustable volume slider for "what-if" analysis.
* Full cost projections for different suppliers based on selected volume and part.
* Graphical view of cost curves helping to identify economies of scale.

### 3. **Make Option Costing**

* Internal cost analysis including:

  * Machine model capacity
  * Capital investment requirements
  * Additional unit capacity needed
* Calculation of full internal manufacturing costs for each part.

### 4. **Make vs Buy Recommendation**

* Comparison of "Make Scenario Full Cost" vs. "Buy Scenario Full Cost".
* Final decision support output (highlighted in green): "Make" or "Buy" for each part.
* Cost avoidance metrics to quantify the financial benefit of the decision.

## 📂 Project Files

* Power BI .pbix file
* Excel source files (quotes, internal production data)
