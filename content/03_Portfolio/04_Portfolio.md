# 📊 Power BI Portfolio: Corporate Training Analytics

## 🎯 Executive Summary
While my academic foundation covers Cybersecurity, my professional "forte" is **Business Intelligence**. This portfolio showcases a comprehensive **Training & Development Dashboard** designed to track organizational learning KPIs, employee participation, and completion rates.

---

## 📈 Dashboard Gallery

### 1. Executive Overview & KPI Tracking
This view provides a high-level summary of training targets versus actual performance.
![[PBI_Overview.png]]
> [!NOTE] Key Insight
> This page tracks "Target Population %" (currently at **47.22%**) and "Total Training Hours" (**14,044**), allowing leadership to see if the organization is meeting its annual development goals at a glance.

### 2. Demographics & Hierarchy Analysis
Understanding *who* is being trained is critical for equitable corporate growth.
![[PBI_Demographics.png]]
- **Gender Distribution:** Shows a breakdown of 64.35% Male and 35.65% Female engagement.
- **Hierarchy Mapping:** Visualizes that "Individual Contributors" make up the largest training block (**1,141** employees).
- **Mode of Training:** Compares Face-to-Face (**56.52%**) vs. Online and Hybrid modes.

### 3. Completion Status & Role Distribution
This view uses slicers to allow for deep-dives into specific training titles and grades.
![[PBI_Status.png]]
- **Completion Rate:** Tracks "Completed" vs "Incomplete" status across various programs like "Manager's Toolbox" and "Safety Training."
- **Global Grade Analysis:** Distributes training data across corporate grade levels (e.g., Grade 11 and 12 showing the highest volume).

---

## 🛠️ Technical Implementation (My "Forte")

### Data Engineering (ETL)
- **Power Query:** Normalized messy HR Excel exports into a clean **Star Schema**.
- **Data Cleaning:** Handled null values in "Actual Attendees" and standardized "Global Grade" naming conventions.

### DAX Calculations
I developed several custom measures to power this dashboard, including:
- **Unique Headcount (HC):** Using `DISTINCTCOUNT` to ensure employees aren't double-counted across different sessions.
- **Response Rates:** A calculated measure comparing "Total Respondents" to "Actual Attendees."

### UI/UX Design
- **Color Theory:** Used a consistent palette (Blue, Gold, Red) to distinguish between different training types and statuses.
- **Interactivity:** Implemented cross-filtering so that clicking a specific "Hierarchy" level updates the entire dashboard to show that group's specific KPIs.

---
[[index|Return to Home Dashboard]]
