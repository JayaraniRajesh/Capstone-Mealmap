Background of Organization:
Foodies can find nearby restaurants with the website MealMap. More people are placing online food orders as a result of COVID-19, and they frequently consult internet evaluations when doing so. MealMap makes it easy for people to identify and order food from nearby restaurants while showcasing specialties to draw in new customers, making it possible for restaurants to stand out from the competition. The primary objective is to support neighbourhood restaurants in growing their customer base and remaining competitive.

Stakeholders:
Restaurant owners and managers in the seven cuisine types analyzed (Korean, Japanese, Chinese, Vietnamese, Thai, French, and Italian) as well as potential investors in the restaurant industry.The founders and investors of MealMap want to expand the company and make money.

Data mining:
Explanatory data analysis is utilized to determine the elements that impact these sentiments while Supervised learning (SVM) is used to categorize restaurant reviews as good, negative, or neutral. 
Potentially predictive, the study can offer suggestions for raising restaurant ratings. Depending on the objectives—individual restaurant reports or professional publications—deployment might differ.

Data description:
Yelp Dataset: An enormous database made up of data about businesses, user reviews, and user information gathered from the Yelp website. The collection contains data on companies with locations in all 50 US states, including restaurants, as well as reviews left by customers.
The precise information used in the analysis is as follows:
Business Table: A table with details on businesses, such as names, addresses, categories, ratings, and other characteristics.
Review Table: A table with details on user reviews, including the content of the review, the user's rating, and the business ID of the business that has been reviewed.
The analysis examines restaurants in seven cuisine types, categorizes them by cuisine using keywords, and labels them positive, negative, or neutral based on ratings. Data is cleaned and transformed, sentiment is extracted using SVM models, and business and review tables are merged for visualization of customer sentiment towards cuisine types.

Data cleaning process:
Data analysis tool used: Python
Data preprocessing:
There were 50 states in the United States it is filtered out.
We have filtered out all restaurants that are only located in the United States.
Data cleaning:
Using the matching keywords, categorized all restaurants on the basis of the type of cuisine they serve.
The records with null categories are deleted.
In the name and address columns, quotation marks have been removed.
Label the restaurants with a rating of above 4 as positive, restaurants with a rating below 3 as negative, and restaurants with a rating of 3 as neural.
The neural label is dropped from the rows.

Implications:
Based on our data analysis we have found that users are prepared to spend extra for restaurants that provide distinctive and sustainable options because they appreciate authenticity and quality, according to our research.
Identify trends and patterns in user behavior that can inform marketing strategies and product development.
Our suggestions include gathering more information on user behavior, running polls and focus groups, and working with eateries to provide special offers and promotions.
We advise MealMap to keep placing a high priority on supporting regional companies and sustainability.

Recommendations
Based on our analysis, our recommendations cover a range of topics, including service, food quality, and decor.
Partner with restaurants to offer exclusive deals and promotions for Meal Map users.
Collect additional data on user behavior, such as search queries, click-through rates, and booking patterns, to further personalize the user experience.
By implementing these recommendations, restaurants can enhance their overall customer experience, increase their ratings and reviews, and attract more customers to their establishments.



