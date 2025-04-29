# B2B Courier Charges Accuracy Analysis

## 📦 Problem Statement

ABC Company operates an e-commerce platform and ships orders using various courier partners. Courier charges are based on product weight and delivery distance. ABC wants to verify the accuracy of charges using internal data and courier invoices.

## 🔍 Goal

To compare expected courier charges (as per ABC’s logic and weight slabs) with actual charges by courier companies and summarize overcharges and undercharges.

## 📊 Data Sources

- Website Order Report (Order IDs, SKUs)
- SKU Master (Product weights)
- Courier Company Invoices (AWB, weights, delivery zones, charges)
- Warehouse PIN-to-Pincode mappings

## ✅ Key Tasks

- Calculate order weights using SKU Master
- Determine expected courier charges based on slab logic
- Compare with actual courier invoices
- Summarize overcharged and undercharged cases

## 📈 Outputs

- Detailed analysis table (Order ID, Total Weight, Delivery Zones, Charges comparison, etc.)
- Summary Table (Correctly charged, Overcharged, Undercharged)

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Jupyter Notebook

---

## 📁 File

- `B2B_Courier_Charges_Analysis.ipynb`: Main notebook containing analysis and results.
