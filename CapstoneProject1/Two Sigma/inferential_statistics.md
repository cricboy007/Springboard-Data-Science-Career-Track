Inferential Statistics
=============

I want to predict how popular an apartment rental listing is based on the listing content like text description, photos, number of bedrooms, price, etc

The target variable, interest_level, is defined by the number of inquiries a listing has in the duration that the listing was live on the site. 

interest_level: this is the target variable. It has 3 categories: 'high', 'medium', 'low'
It is also a dependant variable. It depends on #features and price.
 
Converted interest level column from string to categorical. 
Added photos_count column: number of photos
Added features_count column: number of features
Find correlation between columns 

![](https://github.com/cricboy007/Springboard-Data-Science-Career-Track/blob/master/CapstoneProject1/Two%20Sigma/corr.JPG)

Here are my observations:
#bedrooms has positive correlation with interest level, but it’s hard to conclude anything based on the value
#features and #photos has weak positive correlation with interest level
Interestingly, #bathrooms and price has weak negative correlation with interest level
#bedrooms and number of bathrooms are directly proportional
#features, #photos, #bedrooms and #bathrooms has positive correlation

Null Hypothesis: Price has no effect on interest level. Mean rent is 3830
Alternative Hypothesis: Price has an effect on interest level. In other words mean rent != 3830

I divided dataset into two sets:
*Set1 - Listing below mean rent 3830
*Set2 - Listing above or equal to 3830

After applying T-test using stats.ttest_ind, I got **p-value as  1.1716559094536672e-07.**

**With such a low p-value we can safely deny null hypothesis.
In other words, listing price has an effect on interest level.**

###Links

[Links](https://github.com/cricboy007/Springboard-Data-Science-Career-Track/blob/master/CapstoneProject1/Two%20Sigma/inferential%20statistics.ipynb)
