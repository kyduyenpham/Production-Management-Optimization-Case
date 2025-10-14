# 🧩 1. BUSINESS NEEDS & OBJECTIVES  

**Project Title:** Production Management Optimization for SMEs  
**Prepared by:** Dean Phạm – Business Analyst  

---

## **Business Context**

Small and Medium-sized manufacturing enterprises (SMEs) often rely on manual systems such as Excel sheets and paper records to manage production schedules, inventory, and performance reports.  
This results in **inefficiencies, data inaccuracy, and lack of visibility** across departments (Production, HR, and Quality Control).  

To remain competitive and scalable, these SMEs must **optimize their production management process** through digital transformation — even with limited budgets and resources.

---

## **Business Needs Overview**

| Business Need                                     | Why It’s Important                                                                       | Direction / Tool to Help                                                                           |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Centralize Production Information**             | Data is scattered across multiple spreadsheets; teams can’t access updates consistently. | Deploy a lightweight PMS (Production Management System) like Odoo or ERPNext for unified tracking. |
| **Improve Production Planning Accuracy**          | Manual planning causes scheduling conflicts and resource underutilization.               | Implement automated planning with machine & operator capacity logic.                               |
| **Monitor Machine & Operator Performance**        | Managers lack insight into efficiency, downtime, and bottlenecks.                        | Use simple dashboards that visualize performance metrics (Power BI, Google Data Studio).           |
| **Integrate HR Attendance with Shift Planning**   | HR data is not connected to production shifts, causing delays and payroll mismatches.    | Connect HR attendance via shared database or API into PMS.                                         |
| **Reduce Manual Reporting & Paperwork**           | Manual reports are time-consuming and prone to error.                                    | Automate daily reports and digital forms (e.g., Google Sheet APIs, Airtable, or PMS export).       |
| **Enable Real-time Data Visibility**              | Without live updates, managers make decisions on outdated information.                   | Enable live dashboards or status boards accessible to all departments.                             |
| **Support Decision-Making with Performance KPIs** | No defined metrics for tracking productivity or quality performance.                     | Define KPIs such as OEE, rejection rate, and production lead time to measure improvement.          |

---

## **1. Centralize Production Information**

**Why It’s Important:**
- Each team (Planning, Warehouse, Production, QC) uses its own file.  
- Information gaps cause delays and version conflicts.

**What Needs to Happen:**
- Implement a **centralized PMS** where all updates (inventory, production, QC) are entered once and shared across departments.  
- Configure user permissions to ensure data security while improving accessibility.

---

## **2. Improve Production Planning Accuracy**

**Why It’s Important:**
- Production delays and idle time occur because schedules don’t account for machine maintenance or workforce availability.  
- SMEs often overcommit production without clear resource visibility.

**What Needs to Happen:**
- Automate the planning process using PMS rules:  
  - Machine capacity (hours/day)  
  - Operator skills and shift availability  
- Generate a **daily/weekly plan** that automatically recalculates when resources change.

---

## **3. Monitor Machine & Operator Performance**

**Why It’s Important:**
- Managers don’t know which machines or operators perform efficiently.  
- Without performance metrics, optimization decisions are subjective.

**What Needs to Happen:**
- Install machine sensors or use manual digital logs (via tablets or PMS forms).  
- Calculate **OEE (Overall Equipment Effectiveness)** for each line:  
  `OEE = Availability × Performance × Quality`  
- Visualize performance trends in dashboards.

---

## **4. Integrate HR Attendance with Shift Planning**

**Why It’s Important:**
- Production plans often mismatch with actual attendance → delayed start time, uneven workload.  
- Payroll data must align with attendance and output records.

**What Needs to Happen:**
- Build a simple data link between **HR attendance system and PMS** (e.g., shared Google Sheet or API).  
- Auto-assign shifts based on who checked in.  
- HR and Production share one view of operator availability.

---

## **5. Reduce Manual Reporting & Paperwork**

**Why It’s Important:**
- Supervisors spend hours compiling Excel reports, reducing time for actual supervision.  
- Data transcription errors accumulate, causing inaccurate reports.

**What Needs to Happen:**
- Automate daily production reports in PMS.  
- Reports update automatically based on entered data (e.g., Power Automate, Google AppScript, or built-in PMS report).  
- Output summary: output per machine, downtime, rejection rate, and efficiency.

---

## **6. Enable Real-time Data Visibility**

**Why It’s Important:**
- Management decisions are made on yesterday’s data.  
- Lack of transparency slows down response to production issues.

**What Needs to Happen:**
- Real-time dashboard with line status (Running / Idle / Maintenance).  
- Integrate simple alert system: downtime >30 mins → SMS/Email notification.  
- Managers can view performance from any device.

---

## **7. Support Decision-Making with Performance KPIs**

**Why It’s Important:**
- Without measurable KPIs, improvement is subjective and inconsistent.  
- SMEs need simple, visual metrics to monitor progress.

**What Needs to Happen:**
- Define KPIs that are relevant to SME operations:  
  - Production output per shift  
  - Machine downtime rate  
  - Defect ratio (%)  
  - On-time delivery rate  
- Automate KPI calculation in PMS dashboards.

---

## ✅ **Business Objectives Summary**

| Objective                             | Expected Outcome                          | Business Value                  |
| ------------------------------------- | ----------------------------------------- | ------------------------------- |
| Centralize production operations      | Single source of truth across teams       | ↑ Collaboration & data accuracy |
| Automate scheduling & shift planning  | Less manual work, faster production start | ↓ Delay & idle time             |
| Measure machine & operator efficiency | Identify and improve low-performing areas | ↑ Productivity                  |
| Link HR and Production data           | Accurate payroll & workload tracking      | ↑ Transparency                  |
| Automate reporting                    | Save 2+ hours per day for supervisors     | ↑ Speed, ↓ Error                |
| Introduce KPI dashboards              | Data-driven management culture            | ↑ Accountability                |

---

## 🌟 **Expected Impact for SMEs**

| Metric                  | Before      | After Implementation |
| ----------------------- | ----------- | -------------------- |
| Planning time           | 3–4 hrs/day | <1 hr/day            |
| Manual reporting errors | 20%         | <5%                  |
| Decision latency        | 1 day       | Real-time            |
| Machine downtime        | 15%         | <8%                  |
| Data consistency        | 60%         | 95%                  |

---

## 🧠 **Summary Insight for Portfolio Presentation**

This project focuses on **digital transformation for SMEs** by introducing a **lean and affordable Production Management System (PMS)** integrated with HR and reporting functions.  
It highlights the ability to:
- Identify business problems through observation and stakeholder interviews  
- Translate SME pain points into structured requirements  
- Design lightweight, scalable solutions with measurable outcomes
