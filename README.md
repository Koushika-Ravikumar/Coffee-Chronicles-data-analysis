# The Coffee Chronicles ☕  

Exploratory data analysis project on specialty coffee reviews, focusing on origins, roast levels, ratings, and pricing to uncover consumer and market insights.

## Project Overview

This project analyzes a coffee reviews dataset containing information about coffee name, roaster, roast type, country of origin, price, rating, and review date.The goal is to understand how origin, roast, and price relate to quality ratings and to provide insights that are useful for coffee enthusiasts and businesses.

## Dataset

- Ranks coffees from different countries based on price, country of origin, quality, roast type, reviewer’s country, and consumer ratings.
- Primary sources:
  - Kaggle coffee review dataset.
  - Real‑time review data from CoffeeReview.com, a leading specialty coffee review site.

The analysis focuses on a purposive sample of reviews from the United States and Floyd regions to keep the scope manageable.

## Key Questions

1. What are the most common coffee origins in the United States and Floyd?
2. How do ratings differ across roast levels (light, medium, dark)? 
3. Which origins appear most frequently in highly rated reviews (e.g., rating ≥ 95)?  
4. How does the price range of highly rated coffees compare with lower‑rated coffees?

## Methods

The notebook follows a structured analytics workflow:

- **Data cleaning**
  - Handle missing values and remove irrelevant or duplicate records.
- **Filtering and preparation**
  - Keep only reviews from the United States and Floyd regions.
  - Drop `origin_1` (city‑level) to focus on country‑level origins.
- **Descriptive & comparative analysis**
  - Descriptive statistics for origins and ratings.
  - Compare average ratings across roast types.
  - Identify frequently occurring origins among top‑rated coffees.
  - Analyze price ranges for high‑ vs low‑rated coffees.
- **Visualization**
  - Bar charts for common origins.
  - Box plots for ratings by roast level.
  - Scatter plots of price vs rating.
  - Additional plots to support the business questions.
    
## Use Cases

- **Coffee enthusiasts**: Discover highly rated coffees by origin, roast profile, and price–quality trends.  
- **Roasters, retailers, importers**: Understand consumer preferences to guide sourcing and pricing strategy.
- **Baristas and coffee shops**: Curate menus aligned with popular and highly rated coffees to improve customer experience.

