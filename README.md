# Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange

## Analyzed and Submited by- Saddam Ansari @Aspiring Data Analyst [Linkeldin](https://www.linkedin.com/in/saddam-ansari-dataanalyst)

### Live Dashboard at Novypro [Link](https://www.novypro.com/project/electronic-products-reviews-and-rating-analysis--onyx-data-dna-feb-2024-challenge-by-saddam-ansari-power-bi)

#

## Challange Objective 
The objective of the Onyx Data DNA February 2024 challenge was to analyze a dataset of product ratings and reviews and provide answers to the following questions:

1. What is the relationship between product ratings and recommendation status?

2. Which brands have the highest average customer satisfaction, and how does it vary across different product categories?

3. How do product features (such as color or dimensions) influence reviews and ratings?
#

## Obout Data set
For this project, I was provided with an Excel file containing the following data:

| Column Name |	Description	| Data Type	|
| -- | -- | -- |
| id	| A unique identifier for each product entry | String	|
| brand	| The brand name of the product	| String	|
| categories | The categories the product belongs to, often separated by commas	| String |
| colors	| The color(s) of the product, standardized to lowercase	| String |
| dateAdded	| The date the product was added to the dataset |	DateTime |
| dateUpdated |	The most recent date the product information was updated |	DateTime |
| dimension	| The dimensions of the product, filled with 'Unknown' if missing	| String |
| manufacturer |	The manufacturer of the product, filled with 'Unknown' if missing |	String |
| manufacturerNumber |	The manufacturer's unique number for the product	| String |
| name |	The name of the product |	String |
| reviews.date |	The date of the review, converted to datetime format	| DateTime |
| reviews.dateSeen | 	The date(s) the review was seen, could be multiple dates separated by commas	| String |
| reviews.doRecommend  |	Whether the reviewer recommends the product ('True', 'False', or 'Unknown' for missing data) |	String |
| reviews.numHelpful	| The number of people who found the review helpful, with outliers removed	| Float
| reviews.rating	| The rating given by the reviewer, on a scale from 1 to 5	| Float |
| reviews.text |	The text of the review | 	String |
| reviews.title	| The title of the review	| String |
| reviews.username	| The username of the reviewer	| String |
| sourceURLs	| The URL(s) where the product information was sourced, could be multiple URLs separated by commas	| String |
| upc	| The Universal Product Code for the product	| Float |
| weight | 	The weight of the product, standardized to a string format	| String |

#

## Toolse Used
Based on the requirements of the challenge and my personal interest, I utilized **Power BI**, a powerful business intelligence tool.

## Challenge Sponsered 
The Onyx Data DNA February 2024 challenge is sponsored by **@ZoomCharts**, **@Data Career Jumpstart**, **@DATAcated**, and **@The AI Journal**.

## Dashboard Overview
In response to the challenge request, I have created a Power BI report featuring **five distinct pages** accessed through separate bookmarks. These pages serve as individualized sections, with the first page acting as an overview that addresses the questions posed in the challenge. Additionally, four optional pages have been developed to delve deeper into specific aspects of the analysis.


#
## Questions & Solutions

#### Q1. What is the relationship between product ratings and recommendation status?
#### Solution:-

To address the question regarding the relationship between product ratings and recommendation status, I employed Scatter Plot visuals within my analysis. These visuals provide a clear depiction of the correlation between product ratings and recommendation.

Through my analysis, I discovered a notable trend: products with higher ratings tend to have a higher recommendation rate. This finding aligns with a general consumer behavior phenomenon, where individuals are more inclined to recommend products that they perceive positively, indicating a positive correlation between product ratings and recommendation status.

![Screenshot 2024-02-21 093313](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/f59eb846-325d-4de3-9fbc-ab056da38724)

#

#### Q2. Which brands have the highest average customer satisfaction, and how does it vary across different product categories?
#### Solution:-

To identify brands with the highest average customer satisfaction and understand variations across different product categories, I utilized the **ZoomCharts drill-down combo bar pro visual**, which provided two distinct insights.

Firstly, the visual showcased the top brands by the highest average rating, allowing for a detailed analysis of customer satisfaction levels. Additionally, it presented the top categories by the highest average rating.

Upon closer examination, it became apparent that while the top brands and categories exhibited slightly lower review counts, the sentiment remained predominantly positive. This observation suggests that even categories and brands with review counts ranging from 1 to 200 can achieve top ratings, indicating a consistent level of customer satisfaction.

For more detailed insights, users can hover over the visuals to access additional information.


![2](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/391eb673-d9be-44b7-b0d8-9c4a33d0c0e9)

#
#### Q3. How do product features (such as color or dimensions) influence reviews and ratings?
#### Solution:-
To examine how product features, such as color or dimensions, influence reviews and ratings, I created two separate tables on the main page of my report. These tables provide insights into customer ratings, reviews, and recommendations based on color and dimensions, facilitating an easy comparison of the impact of different features.

![3](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/c750fe96-2aff-4231-ad16-5ddce82b3cb4)


For instance, the analysis revealed that the color black garnered the highest number of reviews, constituting 53.13% of the total reviews, with an impressive average rating of 4.27. Moreover, out of 3878 reviews for black-colored products, 2824 individuals recommended them, underscoring their popularity and favorable ratings.

Similarly, product dimensions were found to play a significant role in influencing reviews and ratings. For example, products with dimensions of 2.2x1.2x7.3 inches received the highest number of reviews, accounting for 21.98% of the total, with an average rating of 3.85. Additionally, out of 1604 reviews for products with these dimensions, 866 individuals recommended them, indicating their positive reception.

Conversely, products with dimensions of 11.6x8.5x0.19 inches boasted the highest average rating of 4.61, based on 507 reviews, with 464 recommendations. This highlights the importance of product dimensions in shaping customer perceptions and preferences.

#

## Optional
### Page 2 Rating Based Analysis:-

In addition to the requested question, I have created a separate page dedicated to insights based on ratings, accessible through bookmarks.

This page features a distribution of ratings, showcasing the number of reviews received for each star rating category (5 stars, 4 stars, 3 stars, 2 stars, and 1 star). Additionally, I have incorporated a visual displaying the average rating by product color, allowing for a comprehensive analysis of color-wise average ratings.

Furthermore, I have included a visualization depicting the distribution of reviews from various sources, enabling users to discern that approximately 81% of the reviews, totaling 5943, originate from Best Buy.

Additionally, a detailed table titled "Distribution of Products by Review, Rating, and Total Recommended" has been created. This table provides a comprehensive overview, detailing the number of reviews, recommendations, and average ratings for each brand. Moreover, the data is further segmented based on sub-categories, offering insights into the distribution of products across different brand categories.

These insights provide valuable information regarding the distribution of ratings, sources of reviews, and brand performance, facilitating a deeper understanding of customer sentiments and preferences.

![Page 2](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/2fe9b717-848b-4c61-ba1e-1e201b93350c)

#

## Optional
### Page 3 Brand Based Analysis:-
On this page, I have curated a series of visuals that provide insights based on brands, utilizing the ZoomCharts drill-down combo bar pro visual for enhanced analysis. Each visual offers a unique perspective on brand performance:

**1. Top Brand by Highest AVG Rating**: This visual showcases the top brands with the highest average ratings, allowing users to identify brands that excel in customer satisfaction.

**2. Bottom Brand by AVG Rating**: Conversely, this visual highlights the brands with the lowest average ratings, enabling users to identify areas for improvement.

**3. Top Brand by Total Number of Reviews**: Here, users can discern the brands that have garnered the highest number of reviews, indicating their level of popularity and engagement with customers.

**4. Bottom Brand by Number of Reviews**: Similarly, this visual identifies brands with the lowest number of reviews, providing insights into areas where brand visibility and engagement may need enhancement.

**5. Top Brand by Number of Recommendations**: This visual illustrates the brands that have received the highest number of recommendations from customers, reflecting their level of customer satisfaction and advocacy.

**6. Bottom Brand by Number of Recommendations**: Conversely, this visual highlights brands with the lowest number of recommendations, suggesting areas where customer satisfaction may be lacking.

![Page 3](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/dab824f7-4df8-428e-9d5a-0145870bb455)

#
## Optional
### Page 4 Category Based Analysis:-

On this page, I have curated a series of visuals focusing on category-based analysis, providing insights into various aspects of product categories. Each visual is presented using the ZoomCharts drill-down combo bar pro visual, offering the flexibility to explore different dimensions of the data.

The visuals include:

1. Top categories by Highest AVG Rating

2. Bottom categories by AVG Rating

3. Top categories by total number of reviews

4. Bottom categories by number of reviews

5. Top categories by the number of recommendations received

6. Bottom categories by the number of recommendations received

These visuals allow users to easily identify the top and bottom-performing categories based on average ratings, total reviews, and recommendations. By leveraging the interactive capabilities of ZoomCharts, users can drill down into specific categories to gain deeper insights and make informed decisions based on the analysis.


![Page 4](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/5fdf9ab4-b786-4208-aa9b-2e8fc5032797)

#

## Optional
### Page 5 Product Based Analysis:-
On the product-based analysis page, I have incorporated a visually appealing layout to enhance user experience. Utilizing a slicer, users can select a specific product, which then displays its image along with relevant details.

The selected product's name, a larger image, its associated color, category, and brand are prominently showcased. Additionally, the number of recommendations received by the product is highlighted.

In the event that a user does not manually select a product, the system automatically chooses one for display.

Furthermore, user-generated feedback and reviews about the selected product are also presented, providing additional insights into its performance and reception.

![Page 5](https://github.com/user-saddam123/Electronic-Products-Reviews-and-Rating-Analysis--Onyx-DataDNA-Feb-2024-Challange/assets/123800896/2c4ae1d1-21fa-409b-bc3b-cb77f1478585)

#

## My Learning
This challenge was a great opportunity to learn and apply advanced data analysis techniques. I also learned how to create visually appealing and informative dashboards that can be used to make data-driven decisions.

also This project has been truly rewarding, allowing me to showcase my work and further my journey as an aspiring data analyst. It not only adds value to my portfolio but also demonstrates my capabilities in handling complex datasets.

## Gratitude
I'm grateful to **Onyx Data** for providing a platform for aspiring data analysts to work on real-time datasets and enhance their skills.

Additionally, I extend my appreciation to **ZoomCharts** for generously offering their premium visuals, which greatly enhanced the project's presentation and analysis capabilities.

I also want to express my gratitude to **Aivis Pavious** from **ZoomChart** for providing valuable guidance on utilizing ZoomCharts visuals effectively.

#

#### Check out my submission and let me know what you think!

Your feedback is highly plays a crucial role in my growth, so please feel free to share any suggestions.

Apart from this project, I have also completed over **20+** **Power BI** projects, which you can explore on **NovyPro** at [NovyPro Portfolio](https://www.novypro.com/profile_projects/saddamansari)

Thank you for taking the time to view my project. I hope you enjoyed it.

#

Created and Analyzed by:

Saddam Ansari @Aspiring Data Analyst [LinkedIn](https://www.linkedin.com/in/saddam-ansari-dataanalyst)

Location: India

### THE END
