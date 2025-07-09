# Indian-General-Elections--2024-Analysis
SQL + Python + Power BI based analysis of 2024 Indian General Election Results with alliance-wise insights and interactive dashboard.
## Project Objective
The objective of this project is to perform an end-to-end data analysis of the 2024 Indian General Election results to uncover insights on party-wise, alliance-wise, and state-wise seat distribution.
It involves using SQL for data extraction and transformation, Python (pandas) for exploratory data analysis (EDA), and Power BI to build an interactive, multi-page dashboard that visualizes the performance of key political alliances such as NDA and I.N.D.I.A.
## 💻 Technologies & Tools Used

🔹 **Python**  
Used for data preprocessing, exploratory data analysis (EDA), and static visualizations.

🔹 **Pandas**  
Handled data cleaning, transformation, and merging multiple datasets for analysis.

🔹 **SQL**  
Performed alliance-wise and state-wise seat aggregation, filtering, and joins to extract structured insights.

🔹 **Matplotlib & Seaborn**  
Created visualizations such as bar plots and pie charts to represent seat distribution and performance comparisons.

🔹 **Power BI**  
Built an interactive multi-page dashboard to showcase insights like NDA vs I.N.D.I.A. performance, state-wise wins, and party-level statistics.

🔹 **Jupyter Notebook**  
Used as the primary development environment for writing and running Python EDA code.

## 🔄 Project Workflow

1. **Data Collection**
   - Gathered raw election datasets from reliable sources (e.g., official CSVs or pre-cleaned sources).
   - Datasets included party-wise results, constituency details, state-wise results, etc.

2. **Data Cleaning & Preparation**
   - Removed duplicates and null values
   - Renamed and standardized column names
   - Merged datasets using `Party_ID`, `State_ID`, and `Constituency_ID` for deeper analysis

3. **SQL-Based Exploration**
   - Wrote complex SQL queries to extract alliance-wise and party-wise seat wins
   - Queried state-wise party performance using JOINs and aggregations

4. **Exploratory Data Analysis (EDA) using Python**
   - Analyzed overall results (NDA vs I.N.D.I.A.)
   - Examined state-level and party-level performance
   - Used pandas, matplotlib, and seaborn for analysis and static plots

5. **Data Visualization**
   - Created bar charts, pie charts, and horizontal bar graphs to visualize seat distribution and comparisons

6. **Power BI Dashboard Creation**
   Built an interactive, multi-page dashboard to visually represent the 2024 Indian General Election results. Each page was designed for clarity, interactivity, and drill-down insights:

🔵 Landing Page:
A navigational page guiding users to different dashboards, featuring thematic categories like Overview, State Demographics, Political Landscape, and Constituency Analysis.

📊 Overview Analysis:
Highlights the seat share of NDA, I.N.D.I.A., and Other parties with alliance-wise total seats, % share, and a visual seat arc. It also includes logos, key party leaders, and alliance breakdowns.

🗺️ State Demographics Analysis:

Interactive maps showing:

State-wise seat distribution by alliance.

Winning candidates per constituency.

Party dominance in each region.

Hover features for vote margins, party names, and candidate info.

🌍 Political Landscape by State:

A dropdown lets you filter by any state.

Shows party-wise results, total seats, and a donut chart for seat share.

Embedded map zooms into selected states with detailed info.

📌 Constituency Analysis:

Displays top stats like total votes, EVM votes, postal votes, and number of candidates.

Comparison cards for winner, runner-up, and second runner-up with vote share and margins.

Great for drilling into specific areas like Patna Sahib, etc.

📋 Details Grid Page:

An Excel-like view of all constituencies, winning/runner-up candidates, total votes, margins, and alliances.

Supports sorting and full data exploration.

7. ## 📊 Results & Insights

### 🟠 Alliance-wise Performance
- **NDA Alliance** secured a **majority with 292 seats (54%)**.
- **I.N.D.I.A. Alliance** won **234 seats (43%)**.
- **Others/Independents** secured the remaining **17 seats (3%)**.

### 🌍 State-wise Trends
- **NDA** dominated in states like **Uttar Pradesh, Bihar, Madhya Pradesh, Gujarat, and Rajasthan**.
- **I.N.D.I.A.** performed strongly in **Kerala, Tamil Nadu, West Bengal, Punjab**, and parts of **Karnataka**.
- Power BI map visuals highlighted **regional strongholds and voting patterns**.

### 🗳️ Constituency-Level Insights
- Each constituency view displayed:
  - **Winning candidate, runner-up**, and **vote margins**
  - **Total votes (EVM + Postal)** and **% of votes**
- Example: In **Patna Sahib**, BJP’s **Ravi Shankar Prasad** won with **54.7% vote share** and a margin of **~1.5 lakh votes**.

### 📌 Party-wise Contributions
- **BJP (NDA)**: 240 seats
- **INC (I.N.D.I.A.)**: 99 seats
- Other significant contributors:
  - NDA: TDP, JD(U), LJP(RV), Shiv Sena (SHS)
  - I.N.D.I.A.: SP, AITC, DMK, RJD, CPI(M), JMM
- SQL was used to calculate **individual party performance** within alliances.

### 📈 Visualization Outcomes
- Developed a **multi-page Power BI dashboard** with:
  - **Overview**: Alliance-wise seat share, party logos, KPIs
  - **State Demographics**: Interactive map with seat splits
  - **Political Landscape**: Filter by state and view party performance
  - **Constituency Details**: Candidate-wise insights and vote margins
- Dashboards were **interactive**, slicer-driven, and **visually intuitive** for end-users.

![Screenshot 2025-07-09 112948](https://github.com/user-attachments/assets/392d2444-b06d-4faf-abbf-6616a64bb4b1)
![Screenshot 2025-07-09 113007](https://github.com/user-attachments/assets/7eabad82-3dfc-4eb0-b09a-be999c58a632)
![Screenshot 2025-07-09 113417](https://github.com/user-attachments/assets/de792168-2784-4647-b042-f35e3f978b00)
![Screenshot 2025-07-09 113127](https://github.com/user-attachments/assets/a33ff984-f92a-4667-9a8c-0ee1806c4505)
![Screenshot 2025-07-09 113105](https://github.com/user-attachments/assets/19612c3a-8579-4e7b-ad51-ca7275ecd169)







