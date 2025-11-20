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

<img width="1122" height="1468" alt="image" src="https://github.com/user-attachments/assets/c7e6601f-548c-4837-8bab-938f4b3154aa" />



## Insights
- **Psychiatry, Long-Term Care, and Palliative Care** show the highest total occupancy, ranging from 55 to 57 percent.
- **Orthopedic, Psychiatry, and Neurosurgery** display the highest ICU occupancy (66 to 67 percent).
- **Emergency Department, General Surgery, and Trauma Center** exhibit the highest non-ICU occupancy (76 to 80 percent).

Across all metrics, the **Emergency Department, General Surgery, and Trauma Center** stand out as departments with high and consistent pressure in terms of filled capacity. These departments may benefit from closer monitoring of patient flow and discharge throughput to prevent operational bottlenecks.

**Psychiatry**, in particular, shows one of the highest ICU occupancy rates and also maintains elevated total occupancy compared to other departments. This combination suggests sustained pressure across both critical care and general bed resources, making it an important area for closer monitoring of patient flow.

## File Included
- **Hospital_Bed_Capacity_ExcelAnalysis_v3.xlsx** – All calculations, metrics, and visualizations.
