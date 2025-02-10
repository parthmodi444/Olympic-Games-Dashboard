# Olympic Games Dashboard: Trends and Achievements

## Overview
The **Olympic Games Dashboard** is an interactive data visualization tool built using **Vega-Lite**. It provides insights into Olympic Games data, including athlete performance, medal distribution, and trends over time. The dashboard allows users to explore data interactively by filtering based on age, country, year, and medal type.

The dashboard is designed to showcase:
- **BMI vs. Age Scatterplot**: Visualizes the relationship between athletes' BMI and age, with color-coded medals and age groups.
- **Medal Count by Country**: Displays the total medals won by each country, with interactive filtering.
- **Yearly Trends**: Shows the distribution of Olympic Games participation over the years.

---

## Features
1. **Interactive Scatterplot**:
   - Explore the relationship between athletes' BMI and age.
   - Filter by medal type (Gold, Silver, Bronze) and age group (Adult, Minor).
   - Tooltips provide additional details like athlete name, gender, team, and sport.

2. **Medal Count by Country**:
   - View the total medals won by each country.
   - Interactive bar chart with filtering based on medal type and country.

3. **Yearly Trends**:
   - Analyze the distribution of Olympic Games participation over the years.
   - Filter by year to focus on specific time periods.

4. **Interactive Filters**:
   - Filter data dynamically using legends and selection tools.
   - Customize the dashboard based on user preferences.

---

## Data Source
The dashboard uses the following dataset:
- **Dataset**: `final5_olympics.csv`
- **Source**: [GitHub Repository](https://raw.githubusercontent.com/parthmodi444/Information-visualisation/refs/heads/main/final5_olympics.csv)

---

## How to Use
1. **Scatterplot**:
   - Hover over points to view detailed information about athletes.
   - Use the legend to filter by medal type or age group.

2. **Medal Count by Country**:
   - Click on bars to filter by country.
   - Use the legend to filter by medal type.

3. **Yearly Trends**:
   - Hover over bars to view the number of games in a specific year.
   - Click on bars to filter by year.

---

## Customization
The dashboard is built using **Vega-Lite**, a high-level visualization grammar. You can customize the visualization by modifying the JSON specification in the code. Key parameters include:
- **Filters**: Adjust the filtering logic in the `transform` section.
- **Colors**: Modify the color scheme in the `encoding` section.
- **Tooltips**: Add or remove fields in the `tooltip` section.

---

## Prerequisites
To use or modify this dashboard, you need:
- A web browser with support for Vega-Lite (modern browsers like Chrome, Firefox, or Edge).
- Basic knowledge of JSON and Vega-Lite syntax.

---

## Running the Dashboard
1. Open the JSON specification in a Vega-Lite editor (e.g., [Vega-Lite Editor](https://vega.github.io/editor/)).
2. Paste the provided JSON code into the editor.
3. Click **Run** to render the dashboard.

Alternatively, you can embed the JSON specification in a web application or use it with a Vega-Lite-compatible library.
---

## Acknowledgments
- **Vega-Lite**: For providing a powerful and flexible visualization framework.

---

## Contact
For questions or feedback, please contact modiparth333@gmail.com.
