# How has COVID-19 Impacted the Development of Airbnb in Singapore?

### Introduction

The COVID-19 pandemic has reshaped various industries worldwide, and the property rental market is no exception. In Singapore, the effects of the pandemic on Airbnb listings have been both complex and far-reaching. The prospective property owners, who once aimed to maximize profits through precise location selection, are now facing a new array of challenges and opportunities. This analysis, conducted by DQLab, aims to provide a comprehensive examination of Singapore's Airbnb property data during these unprecedented times. Utilizing three types of data, including detailed listings, historical rental data, and neighborhood mapping, this study will uncover insights into rental trends, impacts on profitability, and strategies to navigate the evolving landscape. The understanding gained from this analysis will assist property owners in making informed decisions in a market transformed by the global health crisis.

### Data Overview 
#### Data 1: DQLab Airbnb Listing Dataset
This dataset contains information about Airbnb listings in Singapore.

- **File name**: `DQLab_listings(22Sep2022).csv`, `DQLab_listings(22Sep2022).xlsx`
- **Fields**:

  | No | Field Name      | Description                                               |
  |----|-----------------|-----------------------------------------------------------|
  | 1  | id              | Listing's unique Airbnb id                                |
  | 2  | name            | Listing's name/display on the Airbnb website              |
  | 3  | host_id         | Listing host's unique id                                  |
  | 4  | host_name       | Listing host's name                                       |
  | 5  | neighborhood    | Listing's neighborhood name                               |
  | 6  | latitude        | Listing's earth latitude location                         |
  | 7  | longitude       | Listing's earth longitude location                        |
  | 8  | room_type       | Listing's room type                                       |
  | 9  | price           | Listing's price                                           |
  | 10 | minimum_nights  | Indicator of minimum stay length                          |
  | 11 | availability_365| Indicator of the total number of days the listing is available for during the year |

#### Data 2: Listings Reviews History
The second dataset contains historical order/rental data per listing in Singapore from January 1, 2018, to September 22, 2022.

- **File name**: `DQLab_reviews(22Sep2022).csv`, `DQLab_reviews(22Sep2022).xlsx`
- **Fields**:

  | No | Field Name  | Description                               |
  |----|-------------|-------------------------------------------|
  | 1  | listing_id  | Listing's unique Airbnb id                |
  | 2  | date        | Date when the specific listing was rented |

#### Data 3: Neighborhood Mapping
The third dataset contains mapping of Singapore regions based on their neighborhoods.

- **File name**: `DQLab_neighbourhood(22Sep2022).csv`, `DQLab_neighbourhood(22Sep2022).xlsx`
- **Fields**:

  | No | Field Name        | Description                                  |
  |----|-------------------|----------------------------------------------|
  | 1  | Neighborhood_group| Singapore region (North/East/South/West/North-East) |
  | 2  | neighborhood      | Singapore neighborhoods name                 |

### Step-by-Step Interpretation
1. **Import Package**: Importing the necessary libraries for the analysis.
2. **Read Data**: Reading the data from the provided files.
3. **Check Missing Values**: Checking if there are any missing values in the data.
4. **Check Duplicate**: Checking for any duplicate data within the dataset.
5. **Merge Tables with Join**: Merging different tables using join operations.
6. **Convert Data Type**: Converting data types if needed.
7. **Airbnb Price Distribution**: Analyzing the price distribution of Airbnb in Singapore.

### Interpretation During COVID-19
- **Pandemic Impact on Prices**: COVID-19 may have influenced price distribution, with a preference for cheaper prices.
- **Location and Review Factors**: During the pandemic, location and reviews may have become more significant factors, especially if related to cleanliness and safety.

### Business Recommendations
1. **Price Adjustment**: Consider offering more competitive prices to attract guests during the pandemic.
2. **Focus on Cleanliness**: Providing and emphasizing cleanliness protocols can enhance ratings and reviews.
3. **Analyze Strategic Locations**: Offering properties in strategic locations, such as near healthcare facilities or grocery stores, may be more appealing during the pandemic.
4. **Effective Communication with Guests**: Explaining the measures taken to ensure guest safety during the pandemic can build trust and bring in more business.
