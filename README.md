# 💼 Factoring Analytics Dashboard

Welcome to the **Factoring Analytics Dashboard**!  
This Power BI dashboard gives clear insights into a factoring portfolio, including open receivables, overdue invoices, debtor ageing, payments and contracts.

> 📌 Built on **synthetic mock data** (12 clients, 22 contracts, ~770 invoices, ~560 payments). Report labels are in Serbian.

---

## 📁 Repository Structure

1. Factoring-Analytics-Dashboard
2. data — mock dataset (Klijenti, Ugovori, Fakture, Uplate)
3. README.md — main project description

---

## 🌟 Pages Overview

- **Page 1 — Open Receivables**: Open, overdue and not-yet-due amounts by client.
- **Page 2 — Debtors / Ageing**: Number of debtors, largest debtor, ageing buckets (0–30, 31–60, 61–90, 90+ days).
- **Page 3 — Delays**: Overdue amounts by client and contract.
- **Page 4 — Payments**: Total paid, on-time payment %, payments by month and status.
- **Page 5 — Contracts**: Number of contracts and clients, total limit, contract list.

---

## 🔸 Page 1 — Contracts

Shows the contract portfolio: count, clients, limits, factoring types.

<p align="center">
  <img src="https://github.com/GunelXelilli/Factoring-Dashboard/blob/main/FCpage1.png" width="800">
</p>

---


## 🔸 Page 2 — Open Receivables

Shows total open receivables and how much of it is overdue vs. not yet due, split by client.

<p align="center">
  <img src="https://github.com/GunelXelilli/Factoring-Dashboard/blob/main/Fcpage2.png" width="800">
</p>

 ---
 
## 🔸 Page 3 — Payments

Shows payments over time and the share paid on time vs. late.

<p align="center">
  <img src="Factoring4page.png" width="800">
</p>

---

## 🔸 Page 4 — Delays

Shows overdue amounts and average days late by client and contract.

<p align="center">
  <img src="Factoring3page.png" width="800">
</p>

---

## 🔸 Page 5 — Debtors / Ageing

Shows who owes the most and how old the debt is.

<p align="center">
  <img src="Factoring2page.png" width="800">
</p>

---

## 🧮 Data Model

`Klijenti` → `Ugovori` → `Fakture` → `Uplate` (all many-to-one), plus a `Calendar` table and a `Daxs` measure table.

**Key measures:** Open receivables, Overdue amount, Not yet due, On-time payment %, Average / Maximum days late, Number of debtors, Largest debtor.

**Tools:** Power BI Desktop, Power Query, DAX

---

📫 **Contact**

- 🧑‍💻 GitHub: [GunelXelilli](https://github.com/GunelXelilli)  
- 💼 LinkedIn: [Gunel Xelilli](https://www.linkedin.com/in/gunel-xelilli-390bb32b7/)

---

## 🛠️ How to Explore

1. View the screenshots above.  
2. Use the mock data in `data/` to recreate or test the dashboard.  

---

*Created with ❤️ and Power BI skills!* 🎨
