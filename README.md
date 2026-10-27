# hyrule-livability-analysis

## Main Question:

Link has saved Hyrule enough times. Now he just wants to settle down. Where should he build a house if he wants safety, good resources, and easy access to powerful weapons?

## Research Questions:

1. Which regions of Hyrule are the safest for Link to live in?

   - Which region has the fewest bosses and elite enemies?
   - Which region has the lowest overall Danger Score?
   - Which region has the lowest concentration of enemies near potential housing locations?

2. Which regions provide the best access to useful resources (armor, materials Zonai devices)?

   - Which region contains the largest quantity of useful resources?
   - Which region has the greatest variety of resource types?
   - Which region provides the best access to useful resources near potential housing locations?

3. Which regions provide the best access to powerful weapons and Fuse materials?

   - Which region has the most weapon locations?
   - Which region provides access to the strongest weapons?
   - Which region contains materials with the highest Fuse power?
   - Which region offers the best balance of weapon quantity and quality?

4. Which regions are the most convenient for travel and essential services?

   - Which region has the most shrines or fast-travel points?
   - Which region is closest to roads, stables, towns, and shops?
   - Which region provides the shortest travel distance to esesential services?

5. Which region offers the best overall balance of safety, resources, weapons, and accessibility?
   - Which region has the best reward-to-danger ratio?
   - Which region performs consistently across all four categories?
   - Which region receives the highest Hyrule Livability Score?
   - Does the recommended region change when Link’s priorities change?

# Project Structure
├── data/          
│   ├── raw/            - original datasets, unchanged
│   ├── processed/      - cleaned and combined datasets
│   └── reference/      - enemy strength, weapon attack, fuse bonuses, region definitions
├── notebooks/          - exploratory research and statistical analysis
├── src/                - reusable Python functions
├── outputs/
│   ├── figures/        - charts, maps, and visualizations
│   └── tables/         - final analytical tables
├── app/                - interactive Streamlit dashboard
└── tests/              - data and code validation