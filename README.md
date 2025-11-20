# Bed-Occupancy-Micro-Analysis

## Business Context
This micro-analysis simulates how a hospital operations team might evaluate capacity constraints across multiple departments using a summarized bed and ICU dataset.

## Business Question
Which departments exhibit the highest occupancy strain across total beds, ICU beds, and non-ICU beds?

## Data Source
Synthetic Hospital Bed Capacity and ICU Load Dataset  
<https://www.kaggle.com/datasets/endernel/capacity-of-hospitals-bed>

## Metrics
**Total Occupancy Rate**  
Filled beds divided by total beds. Used to assess overall departmental strain.

**ICU Occupancy Rate**  
Filled ICU beds divided by total ICU beds. Highlights pressure on critical care capacity.

**Non-ICU Occupancy Rate**  
Filled non-ICU beds divided by total non-ICU beds. Identifies bottlenecks in general care units.

## Visualization
Excel-based grouped horizontal bar chart comparing all three metrics across hospital departments.  
A checkbox filter was added to dynamically show or hide components of the visualization to make patterns easier to interpret.

<img width="1121" height="1474" alt="image" src="https://github.com/user-attachments/assets/cf3cc332-985e-4b1b-8733-045bb3deab6d" />




## Insights
- **Long-Term Care, Internal Medicine, and Trauma Center** show the highest total occupancy, ranging from 73 to 78 percent.
- **Transplant Unit, Pediatrics General, and Orthopedic** display the highest ICU occupancy (65 to 67 percent).
- **Long-Term Care and Internal Medicine** exhibit the highest non-ICU occupancy, much more than other departments (65 to 75 percent).

Across all metrics, the **Long Term Care and Internal Medicine** stand out as departments with high and consistent pressure in terms of total filled capacity and Non-ICU capacity. These departments may benefit from closer monitoring of patient flow and discharge throughput to prevent operational bottlenecks.

**Pediatrics General, Cardiology,Oncology, Transplant Unit, Burn Unit, and ED** all have noticeably higher occupancy rates for ICU beds compared to non-ICU beds. These departments may benefit from monitoring of referral patterns and further examination of potential inefficiencies in care.

## File Included
- **Hospital_Bed_Capacity_ExcelAnalysis_v3_5.xlsx** – All calculations, metrics, and visualizations.
