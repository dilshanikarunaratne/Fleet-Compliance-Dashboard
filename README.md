# Fleet-Compliance-Dashboard
Power BI dashboard analysing fleet compliance across V5 tracking, tax, disposal, and PNP data integrity, with a focus on identifying root causes and operational risks.

Overview

This Power BI dashboard provides a comprehensive view of fleet compliance, focusing on:

V5 document tracking
Tax and MOT compliance
Disposal management
Private Number Plate (PNP) discrepancies
Operational activity insights

The goal is to identify compliance risks, process gaps, and data inconsistencies across fleet systems.

🎯 Key Features
🔴 Compliance Monitoring
Missing V5 identification and categorisation
Untaxed vehicle tracking
Pending and incorrect disposals
🟠 Root Cause Analysis
V5 root-cause breakdown:
Physical V5 missing
In VVR (registered but awaiting document)
PNP mismatch cases
Expected (new agreements)
🔵 Data Integrity (PNP)
Detects registration mismatches due to private plates
Identifies:
Fleet not updated
Duplicate / split records
🟢 Operational Insights
Travel abroad document tracking
ACK processing trends
Disposal trends
Dealer-level performance
📈 Dashboard Pages
1. Fleet Compliance Overview

Provides a high-level summary of:

Total fleet and active agreements
Total compliance issues
Missing V5 breakdown
Disposal and PNP insights

Key visuals:

Missing V5 breakdown (primary insight)
PNP data integrity chart
Disposal status summary
KPI cards for fleet health
2. Missing V5 Analysis

Focuses on identifying and explaining missing V5 cases:

Root cause categorisation
Dealer-level analysis (who contributes most to missing V5s)
Trend analysis by agreement start date
Filtering by:
Registration
Tax status
Fleet code (VVR)
PNP status

Key insight:

Not all missing V5s are true issues — many are explained by timing, VVR registration, or PNP changes.

3. Operational Drilldown (Recommended)

Provides a detailed, actionable view:

Vehicle-level issue tracking
Prioritisation of compliance issues
Drillthrough capability from summary visuals
🧠 Key Insights
A large portion of missing V5s are not true issues, but:
Already registered in VVR (awaiting physical V5)
Recently added agreements (within grace period)
Affected by PNP registration changes
Dealer-level analysis highlights process inefficiencies and potential onboarding issues
PNP mismatches are a major source of:
Missing V5 records
Duplicate vehicle entries
Tax/VVR inconsistencies
🛠 Tools & Technologies
Power BI
DAX (advanced calculations & categorisation)
Data modelling across multiple operational datasets
📂 Data Sources
Active Fleet File
V5 Records
VVR File
Disposal Log
PNP Records
Travel Abroad Log
ACK Records
🔍 Key Metrics
Total Issues
Missing V5 Count
Untaxed Vehicles
Pending Disposal
PNP Data Integrity Issues
📸 Screenshots
Fleet Compliance Overview

(Insert screenshot here)

Missing V5 Analysis

(Insert screenshot here)

Operational Drilldown

(Insert screenshot here)

🚀 How to Use
Use filters (top bar) to refine:
Registration number
Tax status
Fleet code (VVR)
PNP status
Use charts to:
Identify problem areas
Understand root causes
Drill down into tables for:
Vehicle-level actions
💡 Future Improvements
Automated alerts for compliance breaches
Integration with real-time fleet systems
Predictive insights for V5 delays
Enhanced dealer performance tracking
📌 Notes

This dashboard is designed to:

Highlight actionable issues, not just data
Separate true problems vs explainable scenarios
Support operational decision-making
⭐ If you like this project

Feel free to:

⭐ Star the repo
🍴 Fork it
💬 Suggest improvements
