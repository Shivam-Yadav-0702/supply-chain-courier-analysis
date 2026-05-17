# 📦 Supply Chain & Courier Charge Analysis

## 📌 Objective
Verify courier shipment charges for an e-commerce company by
comparing expected charges vs billed charges to identify
overcharged and undercharged orders.

## 🔍 Business Problem
Courier companies charge based on 0.5 KG weight slabs.
Errors in weight calculation lead to billing discrepancies
that cost businesses significant money.

## 📊 Analysis Areas
- Data Cleaning across 6 source files
- Weight Slab Calculation Logic (0.5 KG intervals)
- Expected vs Billed Charge Comparison
- Overcharged Order Identification
- Undercharged Order Identification
- Distribution & Outlier Analysis

## 💡 Key Findings
- Courier charges depend heavily on weight slab accuracy
- Some orders are overcharged due to incorrect weight calculation
- Automated validation can significantly reduce financial losses
- High-charge shipments need careful monitoring

## 💼 Recommendations
- Validate courier invoices regularly using automated scripts
- Automate weight slab calculations to remove human error
- Monitor high-charge shipments with alert thresholds
- Improve shipment auditing process end-to-end

## 🛠️ Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas & NumPy | Data manipulation & weight calculations |
| Matplotlib & Seaborn | Visualizations |

## 📁 Data Sources
- Courier Company Rates & Invoice
- Company X Order Report & SKU Master
- Pincode Zone Mapping
- BigBasket Products Dataset

## 🚀 How to Run
1. Clone the repo: `git clone <repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Open notebook in Jupyter
