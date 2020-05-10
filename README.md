# E-Commerce
This is a Women’s Clothing E-Commerce dataset revolving around the reviews written by customers. Its nine supportive features offer a great environment to parse out the text through its multiple dimensions. Because this is real commercial data, it has been anonymized, and references to the company in the review text and body have been replaced with “retailer”.

# Content

## This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

#### Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
#### Age: Positive Integer variable of the reviewers age.
#### Title: String variable for the title of the review.
#### Review Text: String variable for the review body.
#### Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
#### Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
#### Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
#### Division Name: Categorical name of the product high level division.
#### Department Name: Categorical name of the product department name.
#### Class Name: Categorical name of the product class name.

# Analysis:

(1)Describing the data
        Descriptive statistics, data type, etc.
(2)Analyzing the text comment/ review 
(3)Converting the ratings into 2 classes
        Class: Bad when Rating <=3
        Class: Good otherwise
(4)Developing a model to predict the Rating class (created above)
        Focus on steps to build a model
        Which algorithm can be used 
(5)Sharing the findings of the model.
