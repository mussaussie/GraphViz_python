🌍 World Happiness Visualization — Grammar of Graphics in Action
Visualizing Global Happiness through the Grammar of Graphics Framework

🧠 Project Overview

This project explores the World Happiness Report dataset using the Grammar of Graphics concept — a structured way to build powerful, layered visualizations in Python.

The goal is to understand how GDP, Health, Freedom, and Corruption influence happiness across countries and regions. The project builds on the ideas shared by Dipanjan Sarkar in his article “A Comprehensive Guide to the Grammar of Graphics”, and reimagines them through a real-world dataset and extended visual analysis.

✨ Key Highlights

Used World Happiness Report (2019) data for a real-world scenario.

Created 2D to 6D visualizations, adding one dimension at a time.

Applied Python’s plotnine library (based on ggplot2 principles).

Revealed how wealth, health, and freedom interact to shape happiness.

Explored how corruption and region affect overall well-being.

🧩 Visual Journey
1️⃣ GDP vs Happiness (2D)
![Alt Text](/output-1%20GDP%20vs%20Happiness.png)


Understanding the core relationship between economic prosperity and national happiness.


2️⃣ Adding Health as Color (3D)
![Alt Text](/output-2%20GDP%20vs%20Happiness%20Colored%20by%20Health.png)


Introducing health (life expectancy) to explore how well-being contributes to happiness.


3️⃣ Adding Freedom as Size (4D)
![Alt Text](/output-3%20GDP,%20Health,%20and%20Freedom%20Effects%20on%20Happiness.png)

Expanding the view by mapping freedom as the size of each country’s marker.


4️⃣ Regional Facets (5D)
![Alt Text](/output-4%20Regional%20Happiness%20Patterns.png)


Breaking down happiness patterns across continents and regions for deeper insight.


5️⃣ Corruption Grids (6D)
![Alt Text](/output-5%20Regional%20and%20corruption-Level%20Comparison.png)


Examining how corruption levels influence happiness within each region.


6️⃣ Regression Trendlines
![Alt Text](/output-6%20GDP%20vs%20Happiness%20by%20Region.png)


Adding linear regression models by region to reveal statistical trends.


💡 Insights Gained

GDP and Health are strong predictors of happiness across nations.

Freedom amplifies happiness — higher freedom corresponds to higher well-being.

Corruption has a consistent negative impact, regardless of economic strength.

Regional context matters — cultural, political, and social differences create unique trends.

The Grammar of Graphics framework allows clear, layered visual storytelling for complex data.

🧮 Tools & Technologies Used

Python 3.10+

pandas — for data manipulation

plotnine — Grammar of Graphics visualizations

matplotlib — base plotting support

Dataset: World Happiness Report (Kaggle)

🔍 Why Grammar of Graphics?

The Grammar of Graphics is a powerful idea — it breaks every visualization into layers like:

Data

Aesthetics (what visual aspects represent data)

Geometry (how data is drawn)

Statistics (optional analytical layers)

Facets (splitting data into subplots)

Coordinates (layout and grid)

Instead of building charts manually, you define rules and mappings, and let the grammar handle the rest — resulting in scalable, elegant visualizations.

🌍 Real-World Applications

This visualization approach is used by organizations like the United Nations, OECD, and World Bank to:

Monitor happiness and well-being indicators.

Identify global inequality trends.

Support data-driven policymaking and social research.

It’s a practical demonstration of how data storytelling can make social data more understandable and impactful.

👏 Acknowledgment

This project is inspired by Dipanjan Sarkar’s article:
A Comprehensive Guide to the Grammar of Graphics for Effective Visualization of Multi-dimensional Data

His explanation of the layered visualization framework guided this implementation, which extends his ideas to the World Happiness dataset for real-world insights.

👤 Author

Abdul Mussavir
📍 Adelaide, Australia

💼 Data Analyst | Data Scientist | Visualization & Insights Specialist | ML Enthusiast

📧 mussaussie@gmail.com

🔗[LinkedIn](https://www.linkedin.com/in/abdulmussavir/)
