# data-512-homework_2
This project includes data and content that are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License. To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/salelbakri/data-512-homework_2.git

## Data Sources
Wikipedia Articles: The dataset of politicians by nationality is available as politicians_by_country_AUG.2024.csv.
Population Data: The population data is sourced from the Population Reference Bureau as population_by_country_AUG.2024.csv.

## Research Implications
This analysis shows clear gaps in Wikipedia's coverage of politicians across countries and regions. Larger, wealthier countries tend to have more articles per capita, and these countries also have a higher proportion of high-quality articles. In contrast, smaller or developing countries are underrepresented both in total coverage and article quality.

## Findings:
- Coverage Gaps: Countries with better internet access and more contributors have significantly more articles. This suggests that access to digital tools and active Wikipedia editors drives coverage.

- Quality Differences: Wealthier countries also tend to have more high-quality articles, while poorer countries have fewer. This reflects a potential bias in information curation on Wikipedia.

- Regional Imbalances: Regions like North America and Europe dominate in both coverage and article quality, while regions like Sub-Saharan Africa and parts of Asia are underrepresented.

## Reflection:
The biggest takeaway is the stark difference in how countries are represented on Wikipedia. Countries with fewer internet users or contributors are less likely to have good coverage. This shows that Wikipedia's global political content may be biased toward wealthier, more connected regions. Addressing these gaps would require targeted efforts to improve Wikipedia's representation of underrepresented countries.

## Question Responses:
What biases did you expect to find in the data (before you started working with it), and why? 

I expected to see coverage gaps, with wealthier countries having more articles and better quality, while poorer countries would have fewer articles. This is based on assumptions about internet access, digital literacy, and active contributors.

What might your results suggest about (English) Wikipedia as a data source? 

Wikipedia is not fully representative. Countries with fewer English speakers will likely use other language editions of Wikipedia, where they might have more articles and better-quality coverage. Relying on the English Wikipedia alone gives a skewed perspective of global information.

Can you think of a realistic data science research situation where using these data might create biased or misleading results?

Yes. If a company used this data to model global interest in political topics, they might wrongly assume that countries with fewer articles are less politically engaged. In reality, those countries might use other language versions of Wikipedia or face barriers to contributing, leading to a biased analysis.

## Results
The results of the analysis are provided in the following tables (available in the Jupyter notebook):
Top 10 countries by coverage: Countries with the highest total articles per capita.
Bottom 10 countries by coverage: Countries with the lowest total articles per capita.
Top 10 countries by high quality: Countries with the highest high-quality articles per capita.
Bottom 10 countries by high quality: Countries with the lowest high-quality articles per capita.
Geographic regions by total coverage: Regions ranked by total articles per capita.
Geographic regions by high quality coverage: Regions ranked by high-quality articles per capita.