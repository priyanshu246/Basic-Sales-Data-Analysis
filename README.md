Project Documentation: Sales Data Analysis Infographic
1. Project Title
2024 Sales Performance: A Visual Analysis Infographic

2. Project Objective
The primary objective of this project is to effectively visualize and communicate key insights from a sales dataset within a single-page application (SPA) infographic. The goal is to present complex data, including KPIs, trends, and comparisons, in an easily digestible, visually compelling narrative, targeting a general audience interested in business performance.

3. Source Material & Data
The infographic is based on a synthetic sales dataset generated programmatically within the Python script. This dataset simulates sales transactions for various products across different regions over a one-year period, including customer satisfaction ratings.

Key Data Points & Metrics Visualized:

Total Revenue: Overall sales generated.

Units Sold: Total quantity of products sold.

Average Customer Satisfaction: Mean satisfaction rating across all transactions.

Sales by Product: Revenue contribution of individual product categories.

Sales by Region: Geographical distribution of sales revenue.

Monthly Sales Trend: Evolution of sales over the months of the year.

Customer Satisfaction vs. Sales (by Product): Relationship between product sales, quantity, and customer satisfaction.

4. Project Structure & Narrative Plan
The infographic is structured as a single, scrollable HTML page designed to tell a coherent story about the 2024 sales performance.

Narrative Flow:

Introduction/Overview (Header): Sets the context and title of the analysis.

Year at a Glance (KPIs): Immediately presents high-level key performance indicators to grasp overall performance quickly.

Goal: Inform (Convey a single important data point)

Visualization: Single Big Numbers (Large, bold text for standout stats).

Justification: Provides immediate, high-impact summary.

Product Deep Dive: Focuses on product-specific performance, identifying top revenue generators.

Goal: Compare (Compare categories)

Visualization: Bar Chart (Horizontal)

Justification: Ideal for comparing values across many discrete categories and sorting for ranking. Implemented with Chart.js.

Regional Sales Breakdown: Analyzes sales distribution across different geographical regions.

Goal: Compare (Show composition)

Visualization: Donut Chart

Justification: Excellent for showing parts-to-whole relationships and compositional breakdowns. Implemented with Chart.js.

Monthly Sales Trend: Explores temporal patterns and seasonality in sales.

Goal: Change (Show change over time)

Visualization: Line Chart

Justification: Best for visualizing trends and movements over a continuous period. Implemented with Chart.js.

Customer Satisfaction vs. Sales: Investigates the relationship between customer satisfaction, product sales, and quantity.

Goal: Relationships (Reveal correlations or distributions)

Visualization: Bubble Chart

Justification: Effective for showing relationships between three variables (X, Y, and size). Implemented with Chart.js.

Our Analysis Process: Briefly outlines the methodological steps taken to arrive at the insights.

Goal: Organize (Show processes)

Visualization: Flow Chart (Implemented using structured HTML/CSS with Tailwind).

Justification: Clearly illustrates sequential steps in a process.

(Neither Mermaid JS nor SVG were used for any diagrams or charts in this project. All charts are rendered via Canvas using Chart.js, and diagrams are built with structured HTML/CSS.)
