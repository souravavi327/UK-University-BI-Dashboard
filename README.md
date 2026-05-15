# Business Intelligence Analysis: UK University Performance (2011-2022)

## Project Overview
This Business Intelligence (BI) project analyses twelve years of higher education performance data from the Guardian University Guide League Tables (2011–2022). The objective was to design an interactive Tableau dashboard that transforms complex, multi-year datasets into actionable strategic insights, specifically focusing on the performance and competitive positioning of the University of the West of England (UWE Bristol).

**Team Members:** Md Zahidul Islam, Mohammad Yeasin Uddin Chowdhury, Sourav Kumar Avi, Manoj Shrestha.

## My Specific Contributions (Sourav Kumar Avi)
As part of this collaborative effort, my core responsibilities bridged the gap between raw data preparation, stakeholder analysis, and interactive dashboard design:

* **Data Cleaning & Imputation:** Processed over 30,000 subject-level records and 1,400 institutional records. I handled widespread missing values by filling categorical gaps with "Unknown", applying year-based medians for numeric gaps, and using forward/backward fill to preserve temporal ranking patterns without data loss.
* **Stakeholder Needs Mapping:** Mapped dashboard requirements to distinct business users (e.g., Executive Leadership needing high-level KPI trends vs. Marketing teams needing "Rising Star" subjects for promotional campaigns).
* **Tableau Prototyping & Design:** Developed the interactive dashboard architecture focusing on relevance, simplicity, and interactivity. This included dual-axis visualisations for ranking trends and multi-line statistical correlation indicators.
* **Strategic Narrative & Recommendations:** Synthesized the data into actionable business insights, such as recommending targeted marketing for subjects with high-ranking momentum (e.g., Film Production and Psychology) and proposing live Tableau monitoring linked to HESA data for university leadership.

## Tools & Technologies Used
* **Tableau Desktop:** Primary tool for data visualisation, interactive dashboard design, and visual analytics (`.twbx`).
* **Data Preparation:** Python/Excel for handling missing values, standardising formats, and structuring relational datasets.
* **Business Analysis:** Trend analysis, competitor benchmarking, and statistical correlation investigation (e.g., Student Spending vs. Satisfaction).

## Repository Structure
* `/data`: Contains the raw and processed CSV datasets, including institution rankings, subject-level data, and competitor mappings.
* `/dashboard`: Contains the packaged Tableau workbook (`BI Dashboard.twbx`). 
* `/reports`: Includes the project documentation, methodology reflections, and the final presentation slides.

## Key Insights Discovered
1. **The Drivers of Success:** Identified that Student Satisfaction (>0.85), Graduate Prospects (>0.80), and Teaching Quality (>0.75) had the strongest statistical correlation with a university's overall national rank.
2. **Subject Volatility & Growth:** Discovered that specific subjects (like Psychology and Film Production) acted as "Rising Stars," rapidly climbing national rankings and aligning with market demand.
3. **Investment vs. Outcome:** Analysed the correlation between 'Spend per Student' and overall student satisfaction, revealing that from 2019-2022, higher spending did not universally correspond with higher satisfaction scores, indicating a need for strategic resource reallocation.

## How to View the Dashboard
To interact with the dashboard, download the `BI Dashboard.twbx` file from the `/dashboard` folder and open it using Tableau Desktop or the free Tableau Reader.
