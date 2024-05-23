# Netflix Dataset Analysis

## Preview
This project analyzes Netflix datasets sourced from Kaggle. The dataset contains information such as title, genre, language, IMDb score, premiere date, runtime, and year.

## Overview
This repository contains analysis conducted on Netflix datasets obtained from Kaggle. The datasets provide valuable insights into the Netflix library, including details about titles, genres, languages, IMDb scores, premiere dates, runtimes, and years.

## Data Source
The dataset used in this analysis was obtained from Kaggle. You can find the original dataset [here](https://www.kaggle.com/datasets/yaminh/netflix-dataset-for-analysis/data).

## Tools Used
- Excel: Utilized for data analysis and visualization.

## Data Cleaning
In the initial preparation phase, the following tasks were performed:

1. **Handling Missing Values**:
   - Identified and handled missing values appropriately. This involved imputation, deletion, or other strategies.

2. **Data Type Conversion**:
   - Ensured each column had the correct data type. Converted data types as necessary (e.g., converting strings to datetime objects).

3. **Removing Duplicates**:
   - Checked for and removed any duplicate rows in the dataset to prevent redundancy.

4. **Final Dataset Preparation**:
   - Prepared the cleaned dataset for analysis by ensuring it was properly formatted and ready for use.

## Exploratory Data Analysis (EDA)

### Overview
The EDA provides a comprehensive exploration of the Netflix dataset, uncovering insights and trends within the data, and answering questions such as:
- What is the general distribution?
- What is the language distribution?

### Summary Statistics
- **Descriptive Statistics**: Calculated summary statistics such as mean, median, mode, standard deviation, and quartiles for numerical variables.
- **Count of Unique Values**: Determined the number of unique values for categorical variables.

### Data Visualization
#### General Distribution (Genre vs. IMDb Score Count)
![image](https://github.com/Sandrakimiring/Netflix-dataset-analysis/assets/168181747/fd5088e8-66a1-45f1-b043-ebed82c1d37a)


#### Language Distribution (Language vs. Title Count)
![image](https://github.com/Sandrakimiring/Netflix-dataset-analysis/assets/168181747/fef38938-0f3c-4ffe-bc80-d4157e73d3ec)


#### Premiere Year Analysis (Premiere Year vs. Genre Count)
![image](https://github.com/Sandrakimiring/Netflix-dataset-analysis/assets/168181747/c8649a32-073e-4577-a594-b5f0bc4c385e)


### Trends and Patterns
- **Popular Genres**: Documentaries have the highest IMDb scores, indicating a preference for factual and insightful content among Netflix viewers.
- **Language Diversity**: English-language titles dominate the Netflix library, suggesting a strong emphasis on content production or acquisition in English.
- **IMDb Scores**: The highest IMDb scores were recorded in 2020, predominantly for English-language titles. This indicates a trend where high-quality content in English was particularly well-received during that year.
- **Premiere Dates**: The year 2019 saw the highest number of content premieres across all genres, highlighting a significant expansion in Netflix’s content offerings during that period.
- **Runtime Analysis**: Further analysis can be done to explore runtime trends, but preliminary observations indicate variability in content length based on genre and year of release.

### Insights
- **Documentary Dominance**: The high IMDb scores for documentaries suggest a strong viewer preference for content that is factual and thought-provoking. This highlights the importance of continuing to invest in high-quality documentary content.
- **Language Strategy**: The dominance of English-language titles underscores the importance of catering to a global audience through English content. However, expanding content in other languages can further enhance Netflix's international appeal.
- **Content Production Surge in 2019**: The peak in content premieres in 2019 reflects Netflix's aggressive content expansion strategy. This period saw a significant increase in the platform’s content offerings, likely aimed at attracting a larger subscriber base.
- **Quality and Language Correlation in 2020**: The high IMDb scores for English-language content in 2020 suggest that high-quality productions in English resonate well with audiences. This emphasizes the need for maintaining high standards in content production, particularly for English-language titles.
- **Audience Preferences and Engagement**: Understanding the preference for documentaries and high-quality English-language content can help Netflix tailor its content strategy to better meet viewer demands and enhance user engagement.
- **Continuous Innovation**: The trends observed underscore the need for ongoing innovation and adaptation to meet evolving consumer preferences. Netflix should continue to invest in diverse content, leveraging data analytics to drive content strategy and maintain its competitive edge.

## Conclusion

The exploratory data analysis of the Netflix dataset revealed several key trends and patterns. Documentaries tend to have the highest IMDb scores, indicating strong viewer preferences for factual and insightful content. English-language titles dominate the Netflix library, reflecting the platform's global reach and the popularity of English content. The peak in content premieres in 2019 showcases Netflix's aggressive content strategy during that year, while the highest IMDb scores in 2020, predominantly for English-language titles, highlight the importance of quality production in driving viewer satisfaction. These insights provide valuable guidance for Netflix in shaping its content strategy and enhancing user engagement.

## Future Work

Future analysis could explore more detailed aspects such as:
- Deeper analysis of user ratings and reviews to understand sentiment.
- Examining the impact of COVID-19 on viewing patterns and content preferences.
- Analyzing the performance of Netflix Originals compared to licensed content.
- Investigating regional preferences and their impact on content strategy.
- Utilizing advanced machine learning models to predict content success based on historical data.

## Usage Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sandrakimiring/netflix-dataset-analysis.git
