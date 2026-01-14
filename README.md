# Airbnb-data-analysis
Analysis data set of Airbnb of 2019 and Draw some strong insights from it
# Airbnb Data Analysis and Insights

## Project Overview
This project focuses on analyzing Airbnb listing data to extract **meaningful insights** about pricing, room types, locations, and availability.

The main objective is to perform **data preprocessing and exploratory data analysis (EDA)** to understand trends and patterns in the Airbnb market.  
No machine learning prediction models are used in this project.

---

## Dataset Overview

### Dataset Name
**Airbnb Listings Dataset**

### Description
The dataset contains information about Airbnb listings, including host details, property characteristics, location, availability, and review-related features.

It is commonly used for:
- Market analysis
- Pricing trends exploration
- Understanding host and customer behavior

---

### Key Features

#### Host Information
- `host_id` – Unique identifier for each host  
- `host_name` – Host name  
- `host_listings_count` – Number of listings managed by a host  

#### Location Information
- `neighbourhood_group` – Broad neighborhood area  
- `neighbourhood` – Specific neighborhood  

#### Property Details
- `room_type` – Type of accommodation (Entire home, Private room, Shared room)  
- `minimum_nights` – Minimum nights required per booking  
- `availability_365` – Availability of the listing throughout the year  

#### Reviews
- `number_of_reviews` – Total number of reviews  
- `last_review` – Date of last review  
- `reviews_per_month` – Average number of reviews per month  

#### Pricing
- `price` – Nightly listing price  

---

## Data Preprocessing
- Removed irrelevant or non-informative columns
- Handled missing values appropriately
- Cleaned and formatted pricing data
- Converted categorical variables into suitable formats
- Ensured consistency and usability of the dataset for analysis

---

## Exploratory Data Analysis & Insights

After cleaning and preprocessing the dataset, exploratory data analysis was performed to answer key business and analytical questions.  
Below are insights derived from the analysis:

### 1. Distribution of Listing Prices
- Most Airbnb listings are priced in the **low to mid price range**.
- Very high-priced listings are comparatively rare.

### 2. Most Common Room Type
- **Entire home/apartment** listings are the most common, followed by **private rooms**.
- **Shared rooms** form a very small portion of total listings.

### 3. Room Type vs Price
- Entire homes/apartments generally have **higher prices** than private and shared rooms.
- Shared rooms are consistently the **cheapest option**.

### 4. Neighbourhood Group with Maximum Listings
- Certain neighbourhood groups dominate the market with the **highest number of listings**.
- These areas are typically popular tourist or city-center locations.

### 5. Neighbourhood Group vs Average Price
- Central or premium neighbourhood groups show **higher average prices**.
- Outer neighbourhoods tend to have **lower average prices**.

### 6. Availability of Listings
- Many listings are available for **most of the year**, while some have very limited availability.
- Low availability often indicates **high demand**.

### 7. Availability vs Price
- Listings with **lower availability** tend to have **higher prices**.
- Highly available listings are generally more affordable.

### 8. Minimum Nights Requirement
- Most listings allow **short stays**, typically 1–3 nights.
- Long minimum-night listings are less common and target long-term guests.

### 9. Minimum Nights vs Price
- Listings with higher minimum-night requirements tend to have **moderate pricing**.
- Very expensive listings usually allow shorter stays.

### 10. Number of Reviews Distribution
- A large number of listings have **few or moderate reviews**.
- Only a small number of listings have very high review counts.

### 11. Reviews vs Price
- Moderately priced listings often receive **more reviews**.
- Extremely expensive listings usually have **fewer reviews**, indicating niche demand.

### 12. Reviews per Month
- Most listings receive **low to moderate reviews per month**.
- Highly reviewed listings are typically active and competitively priced.

### 13. Host Listings Count
- Most hosts manage **only one listing**.
- A small number of hosts manage **multiple properties**, indicating professional hosting.

### 14. Host Listings Count vs Price
- Hosts with multiple listings usually offer **competitive pricing**.
- Single-listing hosts sometimes charge higher prices for unique properties.

### 15. Relationship Between Price and Reviews per Month
- Listings with steady monthly reviews tend to have **reasonable pricing**.
- Very high-priced listings often have lower review activity.

### 16. Popular Neighbourhoods
- Certain neighbourhoods consistently show **high listing density**.
- These neighbourhoods are generally well-connected and tourist-friendly.

### 17. Overall Market Insight
- Airbnb pricing is influenced by **room type, location, availability, and demand indicators** such as reviews.
- The market shows a balance between affordability and premium offerings.

---

## Key Takeaways
- Room type and location are the strongest factors affecting price.
- Availability and reviews act as indicators of demand.
- Most hosts are individuals rather than large-scale operators.

---

## Conclusion
This project demonstrates how **data preprocessing and exploratory data analysis** can uncover meaningful insights from Airbnb data without building prediction models.

The insights can help stakeholders understand market behavior, pricing trends, and customer preferences.


## Key Takeaways
- Room type and location play a major role in determining listing price.
- Availability and reviews provide useful indicators of demand and popularity.
- Airbnb pricing reflects a balance between accessibility, location desirability, and accommodation type.

---

## Conclusion
This project demonstrates how effective data preprocessing and exploratory data analysis can uncover valuable insights from Airbnb listing data.

These insights can help:
- Hosts optimize listing strategies
- Customers understand pricing trends
- Analysts study short-term rental markets

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
