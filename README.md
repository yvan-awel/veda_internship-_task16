# VEDA Technology Internship — Task 19: Top 10 Products

**Intern:** Awelba Yvan Donald  
**Track:** Data Analytics  
**Level & Day:** Level 1, Day 19  
**Company:** VEDA TECHNOLOGY  

---

## 📌 Project Overview

This repository contains the complete implementation for **Task 19: Top 10 Products** under the VEDA Technology Data Analytics Internship Program. The primary objective is to group transactional sales data by product, rank products in descending order of revenue, evaluate revenue concentration via Pareto analysis, and construct a horizontal bar chart visualization.

---

## 📊 Top 10 Products Summary

| Rank | Product Name | Orders | Total Sales ($) | Total Profit ($) | Profit Margin (%) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| **1** | **BPI Conference Room Table** | 39 | $144,300.00 | $10,146.00 | 7.03% |
| **2** | **Canon ImageCLASS Copier** | 31 | $130,890.00 | $39,267.25 | 30.00% |
| **3** | **Herman Miller Ergonomic Task Chair** | 48 | $116,640.00 | $17,517.50 | 15.02% |
| **4** | **Samsung Galaxy S24** | 27 | $112,050.00 | $15,086.73 | 13.46% |
| **5** | **Apple iPhone 15 Pro** | 23 | $99,935.00 | $15,984.00 | 15.99% |
| **6** | **Bush Mission Oak 4-Shelf Bookcase** | 49 | $84,603.00 | $6,115.20 | 7.23% |
| **7** | **HP LaserJet Pro Multifunction Printer** | 24 | $45,540.00 | $1,683.00 | 3.70% |
| **8** | **Krups 12-Cup Programmable Coffee Maker** | 39 | $22,770.00 | $3,295.45 | 14.47% |
| **9** | **Fellowes Heavy-Duty Storage Boxes 12pk** | 35 | $17,100.00 | $2,850.00 | 16.67% |
| **10** | **Logitech MX Master 3S Mouse** | 24 | $10,071.39 | $3,489.75 | 34.65% |
| **TOTAL** | **Top 10 Aggregated** | **339** | **$901,751.85** | **$115,434.88** | **14.73%** |

---

## 💡 Technical Interview Responses

### Q1: How do you handle ties in ranking?
**Answer:**  
In SQL/Excel/Python, handle ties using standard competition ranking (`RANK.EQ`), dense ranking (`DENSE_RANK`), or fractional ranking (`RANK.AVG`). Introduce secondary tie-breakers (e.g. Net Profit) for a unique order.

### Q2: Why use Top 10 analysis?
**Answer:**  
Top 10 analysis leverages the Pareto Principle (80/20 Rule) to focus managerial resources on core drivers. Here, 10 products account for 84.39% of total revenue and 92.78% of net profit.

---

**Author:** Awelba Yvan Donald — VEDA Technology Data Analytics Track
