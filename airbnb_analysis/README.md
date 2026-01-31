# Airbnb Market Analysis: Columbus vs New York

## Author
[Andrew Shroder]

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to support decision-making for travelers, hosts, and potential investors by identifying pricing patterns, availability trends, and market characteristics across the two cities.

## Research Questions

1. Which neighborhoods offer the lowest average nightly price relative to availability?
2. How does listing availability differ between Columbus and New York City?
3. Do hosts with multiple listings charge higher or lower prices than single-listing hosts?
4. How does room type affect pricing across cities?
5. Are highly reviewed listings priced differently than listings with few or no reviews?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | Neighborhood value comparison | price, neighbourhood, availability_365 | listings.csv | Structured |
| 2 | Availability differences by city | availability_365, city | listings.csv | Structured |
| 3 | Host listing behavior | host_id, calculated_host_listings_count, price | listings.csv | Structured |
| 4 | Pricing by room type | room_type, price | listings.csv | Structured |
| 5 | Reviews vs pricing | number_of_reviews, reviews_per_month, price | listings.csv | Structured |

## Data Overview
- **Columbus, Ohio:** 2,877 listings (as of Sept 26, 2025)
- **New York City:** 36,261 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created
