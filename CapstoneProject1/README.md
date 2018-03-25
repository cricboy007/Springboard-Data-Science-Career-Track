Keeping it Fresh: Predict Restaurant Inspections

What is the problem you want to solve?
The goal for this problem is to use data from social media to narrow the search for health code violations in Boston. You will have access to historical hygiene violation records from the City of Boston — a leader in open government data — and Yelp's consumer reviews. The challenge: Figure out the words, phrases, ratings, and patterns that predict violations, to help public health inspectors do their job better.

Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
The City of Boston regularly inspects every restaurant to monitor and improve food safety and public health. As in most cities, health inspections are generally random, which can increase time spent on spot checks at clean restaurants that have been following the rules closely — and missed opportunities to improve health and hygiene at places with more pressing food safety issues.
Each year, millions of people cycle through and post Yelp reviews about their experiences at these same restaurants. The information in these reviews has the potential to improve the City’s inspection efforts, and could transform the way inspections are targeted.
 
What data are you going to use for this? How will you acquire this data?
	Data is freely available for non commercial use at https://bit.ly/2GlrPQx
In brief, outline your approach to solving this problem (knowing that this might change later)
General process to follow:
Analysis of data: pull data into dataframe using pandas, do describe, come up with a strategy to fill up or ignore missing values
Analysis of structured data
Analysis of unstructured data

Data Modeling using clusters:
Got inspected
Not inspected

Plot box plot, charts, identify words that indicate some issue, look for co-linear and covariance fields.  

What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

Working code in python jupyter notebook on github.
Paper explaining EDA, modeling and accuracy of solution
Youtube presentation using slides explaining EDA, modeling and accuracy of solution