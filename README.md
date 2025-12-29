# Zomato-Data-Analysis-Project
Exploratory Data Analysis (EDA) of Zomato data to visualize restaurant performance, ratings, and online ordering trends using Pandas &amp; Seaborn
Here is a professional and detailed README.md content in English that you can use for your GitHub repository.

Zomato Restaurant Data Analysis 🍴
📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a Zomato dataset to uncover trends in the restaurant industry. By analyzing restaurant types, customer ratings, pricing, and service features, this project provides actionable insights for business owners and food enthusiasts.

🗂️ Dataset Description
The dataset contains information about 148 restaurants with the following attributes:

name: Name of the restaurant.

online_order: Whether the restaurant accepts online orders.

book_table: Whether table booking is available.

rate: Customer rating (out of 5).

votes: Total number of ratings/votes received.

approx_cost(for two people): The average cost of a meal for two.

listed_in(type): The category of the restaurant (e.g., Buffet, Dining, Cafe).

🛠️ Tech Stack
Language: Python

Libraries:

pandas: Data manipulation and cleaning.

numpy: Numerical computations.

matplotlib: Basic plotting and visualization.

seaborn: Advanced statistical data visualization.

🔍 Analysis & Key Questions
The notebook explores several critical business questions through data:

Data Cleaning:

Handled the rate column by stripping the "/5" suffix and converting it into a float format to enable mathematical calculations.

Verified that there are zero null values, ensuring high data integrity.

Restaurant Type Distribution:

Analysis: Used countplot to identify which service categories are most common.

Insight: Determines whether the market is dominated by quick-service cafes or formal dining.

Customer Engagement (Votes):

Analysis: Grouped data by restaurant type and summed the total votes.

Insight: Reveals which types of restaurants are most "talked about" or popular among active reviewers.

The Impact of Online Ordering:

Analysis: A comparative analysis of restaurants that offer online ordering versus those that do not.

Insight: Helps understand the digital adoption rate in the industry.

Pricing vs. Service (Heatmap Analysis):

Analysis: Created a Pivot Table and a Heatmap to correlate restaurant types with online order availability.

Visual: Used the YlGnBu (or custom) color palette to show the density of restaurants across these two categories.

📊 Key Insights & Findings
Average Dining Cost: The mean cost for two people is approximately 418 units, suggesting a mid-range market dominance.

Rating Health: Most restaurants maintain a healthy rating, though there is room for improvement in the lower-voted categories.

Service Gaps: The heatmap analysis identifies which restaurant types (like formal dining) have the lowest adoption of online ordering, representing a potential growth area for delivery apps.

💡 Strategic Recommendations
For New Owners: Target a price point between 200 and 500 for a meal for two to capture the largest customer segment.

For Existing Businesses: Restaurants with high ratings but low votes should focus on "Call to Action" marketing to encourage customers to leave reviews, which increases visibility.

Digital Pivot: Casual dining spots should integrate online ordering to compete with the high-engagement levels seen in the Cafe and Quick Bite categories.
