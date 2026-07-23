# Advanced E-Commerce Analytics

> **In-depth data analysis and case studies on e-commerce sales data to uncover revenue trends, customer behavior patterns, and actionable business insights**

---

## 📋 Project Overview

This project performs a **comprehensive exploratory data analysis (EDA)** on an e-commerce dataset, investigating revenue drivers, customer demographics, satisfaction metrics, and discount strategies. The goal is to extract **non-obvious behavioral patterns** and translate them into **data-driven business recommendations**.

### Key Questions Explored

- What product categories and customer segments drive the most revenue?
- How do discount strategies correlate with purchase volume and satisfaction?
- What are the demographic profiles of high-value vs. low-value customers?
- Are there seasonal or temporal patterns in sales performance?
- What factors most strongly predict customer satisfaction?

---

## 🗂 Repository Structure

```
advanced-ecommerce-analytics/
├── advanced_ecommerce_analytics.csv      # E-commerce dataset
├── dataAnalysis_practis.ipynb            # Main analysis notebook (full EDA)
├── Screenshot from 2025-08-14 *.png      # Visualization outputs (10+ plots)
└── README.md
```

---

## 🔬 Analysis Breakdown

### 1. Data Exploration &amp; Cleaning

- Loaded and inspected the e-commerce dataset
- Handled missing values, duplicates, and inconsistent entries
- Converted data types (dates, currencies, categories)
- Created derived features (e.g., profit margin, discount percentage)

### 2. Revenue &amp; Sales Analysis

- **Revenue by category:** Identified top-performing and underperforming product lines
- **Revenue over time:** Analyzed temporal trends and seasonal patterns
- **Price vs. quantity tradeoffs:** Explored how pricing strategies affect sales volume

### 3. Customer Demographics &amp; Segmentation

- **Age, gender, location distributions** across the customer base
- **Purchase frequency analysis:** Identified repeat vs. one-time buyers
- **Customer value segmentation:** Grouped customers by spending behavior

### 4. Discount Strategy Analysis

- **Discount vs. revenue correlation:** Do bigger discounts drive more revenue?
- **Discount effectiveness by category:** Which product types benefit most from promotions?
- **Satisfaction impact:** Do discounted purchases lead to higher or lower satisfaction?

### 5. Customer Satisfaction Drivers

- **Rating distributions** across products and categories
- **Correlation between delivery time, price, and satisfaction**
- **Key satisfaction predictors** identified through cross-tabulation and visualization

---

## 📊 Visualizations

The analysis produced over 10 visualization outputs including:

- Revenue distribution charts (bar, pie, histogram)
- Time-series sales trend plots
- Customer demographic breakdowns
- Discount vs. revenue scatter plots
- Satisfaction heatmap by category
- Correlation matrices

*See the `Screenshot from 2025-08-14 *.png` files for the full set of visualizations.*

---

## 🛠 Technologies &amp; Libraries

| Tool | Purpose |
|------|---------|
| **Pandas** | Data manipulation, cleaning, aggregation |
| **NumPy** | Numerical operations, derived features |
| **Matplotlib** | Core visualizations |
| **Plotly** | Interactive charts |
| **Seaborn** | Statistical visualizations, heatmaps |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 🚀 Usage

```bash
# Clone the repository
git clone https://github.com/heba266/advanced-ecommerce-analytics.git
cd advanced-ecommerce-analytics

# Install dependencies
pip install pandas numpy matplotlib plotly seaborn jupyter

# Open the notebook
jupyter notebook dataAnalysis_practis.ipynb
```

---

## 💡 Key Findings

> *Note: Detailed findings are documented in the Jupyter notebook with supporting visualizations.*

- Identified clear revenue concentration in specific product categories
- Discovered non-linear relationship between discount percentage and purchase volume
- Revealed distinct customer segments with different behavioral patterns
- Found actionable correlations between delivery metrics and customer satisfaction

---

## 🔗 Related Projects

| Repository | Description |
|------------|-------------|
| [uber_data_analysis](https://github.com/heba266/uber_data_analysis) | Uber trip analysis with PCA + K-Means clustering |
| [people_management_analysis](https://github.com/heba266/people_management_analysis) | HR analytics with transformer-based NLP |
| [Machine_learning_labs](https://github.com/heba266/Machine_learning_labs) | ML algorithms: KNN, Neural Nets, Clustering |

---

## 👤 Author

**Heba El-Afifi** — Computer &amp; Communication Engineering, Alexandria University  
📧 iheba3930@gmail.com | 🐙 [github.com/heba266](https://github.com/heba266)

---

## 📄 License

This project is released under the MIT License.
