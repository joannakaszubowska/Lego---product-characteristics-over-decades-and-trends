# Lego- product characteristics and trends over decades 
1. Business Problem
Background:
LEGO, one of the most recognized brands in the toy industry, has continuously evolved its product offerings over the decades. Understanding the trends and characteristics of LEGO products can provide valuable insights into market demands, product development, and consumer preferences. Analyzing these trends from 1970 to 2022 can help LEGO and its stakeholders make informed decisions regarding future product lines, marketing strategies, and target demographics.
Problem Statement:
The main business problem is to identify and understand the trends and characteristics of LEGO products over the years. This includes analyzing the year of production, the average number of pieces per set, the percentage distribution of different categories, identifying the top 10 themes, and understanding product trends among users of the Brickset.com website, including their ratings.
Objective:
To provide a comprehensive report on the evolution of LEGO products over the years and how they are perceived by users. This will help LEGO strategize future product developments and marketing campaigns based on historical data and user preferences.

2. Solution Approach
Data Collection: The analysis is based on the official dataset for the Maven Power Outage Challenge https://www.mavenanalytics.io/data-playground?page=1&pageSize=5. And dataset from https://mostwiedzy.pl/en/open-research-data/data-on-lego-sets-release-dates-and-retail-prices-combined-with-aftermarket-transaction-prices-betwe,10210741381038465-0
The first dataset includes the following columns:
 set_id: A unique identifier for each LEGO set.
 name: The name or title of the LEGO set.
 year: The year the LEGO set was released.
 theme: The overarching theme or category to which the LEGO set belongs.
 subtheme: A subcategory or subgroup within the theme.
 themeGroup: A higher-level grouping of themes for organizational purposes.
 category: The category of the LEGO set (e.g., Normal, Vintage, Licensed).
 pieces: The number of LEGO pieces included in the set.
 minifigs: The number of minifigures included in the set.
 agerange_min: The minimum recommended age range for the set.
 US_retailPrice: The retail price of the LEGO set in the United States.

The second dataset contains the following columns (only those I used in the project): 
setID – internal Brickset.com LEGO set identification number, 
number – official LEGO set ID, 
ownedBy – number of brickset.com users claiming that he or she owns the set,
wantedBy – number of brickset.com users claiming that he or she wants to buy the set,
rating – average set rating according to brickset.com users,
reviewCount – number of the set reviews written by brickset.com users,

3. Data Processing:
To solve this business problem, a structured data analysis approach was taken:
Data Preparation and Loading:
The provided dataset was imported into Power BI.
Data was cleaned and transformed using Power Query to ensure consistency and accuracy.
Data Modeling:
Relationships between tables were established to create a robust data model.
Measures and calculated columns were defined using DAX (Data Analysis Expressions).
Visualization and Reporting:
Interactive dashboards and reports were built in PowerBi to present the data visually.

4. Key Questions Driving the Analysis
- How have the number, variety, and price range of LEGO sets changed over the decades?
- What patterns can be observed in the allocation of LEGO sets among different categories, theme groups, and themes?
- In what ways have the number of pieces and the inclusion of minifigures in LEGO sets changed over time?
- How has the average number of pieces per LEGO set evolved from 1970 to 2022?
- What are the most popular LEGO sets among brickset.com users in terms of the number of sets they own and which ones they would like to have?
- What are the relationships between popularity and LEGO set categories and themes, number of pieces, and year of production?
- What trends can be observed in user ratings and the number of reviews from Brickset.com?

5. Findings:
 1.Average Pieces and New Sets by Year
The average number of pieces per set has steadily increased over the decades, peaking after 2000, indicating a growing trend towards more complex builds.
 2.Correlation between number of pieces and popularity:
Sets with more pieces tend to show higher desire. The scatter plot shows positive correlation between the "Ownedby" and "wantedby" metrics for lego sets. Sets with higher "ownedby" counts tend to have higher "wantedby" counts, indicating that popular sets are both widely collected ang highly sought after.
 3. Average Metrics:
The average number of WantedBy entries (1.1k) is lower compared to OwnedBy entries (3.5k), suggesting that LEGO sets are more likely to be collected than actively sought after by new customers.
 4. Correlation Between OwnedBy, WantedBy, and Rating:
Sets with higher "OwnedBy" and "WantedBy" counts generally show higher ratings, though some lower-rated sets still attract attention.
 5. Rating Distribution:
The majority of ratings cluster between 3.5 and 4.5 stars, with fewer sets receiving extremely low or high ratings.
 6. Correlation Between Retail Price and Rating:
Higher-priced sets tend to have better ratings, suggesting that consumers associate higher prices with quality or that premium sets meet expectations more effectively.

6. Business Implications:
1. Focus on Licensed Themes:
The dominance of licensed themes suggests a strong preference for partnerships with popular franchises. Expanding partnerships with popular franchises could further increase sales.
2. High attractiveness of piece count:
Sets with higher piece counts are perceived as more desirable, indicating a demand for more detailed and complex builds among collectors and enthusiasts.
3. Sustained interest in older sets:
The growing interest in sets from the 2000s suggests a growing secondary market and nostalgia-driven demand. LEGO could capitalize on this by re-releasing classic sets or creating anniversary editions.
4. Opportunities for lesser-known themes:
While licensed themes dominate, there is untapped potential in promoting original themes or those that have a lasting appeal.
5. Theme Perception:
Thematic disparities in ratings suggest that themes like "Educational" and "Art and Craft" may require improved designs or more targeted marketing to align with consumer expectations.
 
7. Recommendations:
1. Introduce new licensed themes tied to popular movies, TV shows or games. Keep the offering fresh to keep the excitement alive among collectors.
2.Introduce high-complexity sets:
Design more sets with more pieces to meet the demand for advanced building experiences.
3.Improve marketing for underappreciated themes:
Allocate resources to promote mid-sized themes like “City” or “Model Building” through targeted campaigns or partnerships with influencers in the LEGO community.
4. Encourage Customer Reviews:
Implement initiatives (e.g., discounts, contests, or rewards) to encourage customers to rate products, particularly for unrated sets.
5.Leverage Top-Rated Sets:
Use top-rated sets like the "Parisian Restaurant" as benchmarks for future product development. Highlight these sets in marketing campaigns to attract potential buyers.
6. Premium Set Strategy:
Continue focusing on high-quality, complex, and premium sets, as they drive higher ratings and consumer satisfaction.

8. Conclusion:
The analysis provided a comprehensive understanding of LEGO product characteristics and trends over decades. The insights gained will assist LEGO in aligning its product development and marketing strategies with historical data and current user preferences, ensuring continued success in the toy industry.
