# 📊 MTSS-Early-Warning-System
![Dashboard Preview](02_Dashboards/dashboard_preview.png)
Complete data architecture and operational templates for a K-12 Early Warning System (EWS) and Multi-Tiered System of Supports (MTSS) framework.

## Overview
This folder contains the complete architecture and operational templates for an integrated **Early Warning System (EWS)** and **Multi-Tiered System of Supports (MTSS)**. 

Designed for K-12 education leaders, this system bridges the gap between data identification and student intervention. It moves beyond a traditional dashboard by providing a "closed-loop" framework: transforming academic, attendance, and behavior metrics into clear risk classifications, and then routing those insights directly into structured action workbooks for teachers, coaches, and administrators. 

## ✨ Key System Features
* **Automated Risk Stratification:** Logic that categorizes students into Tier 1 (On-Track), Tier 2 (At-Risk), and Tier 3 (Immediate Action) based on MAX risk across Academic, Attendance, and Behavior domains. 
* **Decision Layer (Visibility):** High-level visual reporting to monitor school-wide trends, tier distributions, and priority statuses.
* **Action Layer (Operational Workbooks):** Tiered Excel infrastructure allowing seamless data access at the School-Wide, Content Area, Course, and Teacher levels.
* **Closed-Loop Monitoring (RTI):** Dedicated tracking for interventions to ensure educators can monitor response effectiveness over time.

## 📁 Folder Structure
The files in this directory represent the entire lifecycle of the EWS system, categorized by their operational function:

### 1. System Documentation & Methodology
* `MTSS_From_Early_Warning_to_Action.pptx`: The core slide deck explaining the system's architecture, risk calculation rules, and stakeholder workflows.

### 2. The Decision Layer (Visual Dashboards)
* `ANON_MTSS_EWS_25-26.pdf`: A sanitized visual export of the Power BI dashboard showing school-wide tier distributions, risk profiles, and dynamic demographic filtering.

### 3. The Action Layer (Intervention & EWS Workbooks)
These spreadsheets represent the operational routing of the data, ensuring the right stakeholders get the right student lists.
* **School-Wide Level:**
  * `ANON_EWS.xlsx`: The master early warning list for school leadership.
  * `ANON_ATTENDANCE_INTERVENTIONS.xlsx`: Targeted roster for attendance-specific outreach.
  * `ANON_BEHAVIOR_INTERVENTIONS.xlsx`: Targeted roster for behavior and conduct support.
  * `ANON_RTI .xlsx`: The Response to Intervention (RTI) tracker for continuous progress monitoring.
* **Content & Course Level:**
  * `MATHEMATICS_EWS.xlsx`: Consolidated view for Content Leads and Assistant Principals overseeing the Math department.
  * `ALG1_EWS.xlsx`: Course-specific data for Algebra 1 instructional coaches.
  * `ALG1_ACADEMIC_INTERVENTIONS.xlsx`: Specific academic intervention targeting for Algebra 1 students.
* **Classroom Level:**
  * `TEACHER A_EWS.xlsx`: The teacher-facing workbook providing immediate classroom action steps and roster tracking.

## 🔒 Privacy & FERPA Compliance
Student data privacy is paramount. **There is absolutely no live, identifiable, or confidential student data in this folder.** 
All `.xlsx` and `.pdf` files that use the "ANON" naming convention contain sanitized, mathematically generated mock datasets created for demonstration purposes. This ensures full compliance with the Family Educational Rights and Privacy Act (FERPA) while accurately demonstrating the system's capabilities.

## 📬 Contact & Connect
I am passionate about building solutions that bridge Business Intelligence, Data Analytics, and Education—turning data into actionable insights that drive measurable student impact. 

* **LinkedIn:** [Kenier Ramirez, M.Sc. Data Analytics](https://www.linkedin.com/in/kenier-ramirez-m-sc-in-data-analytics-9456a725a)
* **Email:** kenierramirez91@gmail.com
