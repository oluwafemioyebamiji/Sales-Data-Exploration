# Sales Dataset Exploration
## by Oluwafemi Oyebamiji


## Dataset

> Sample Sales Data was inspired for retail analytics and was originally used for Pentaho DI Kettle. This is downloaded from the Kaggle url: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data

> There are 2,823 samples and 19 features in the dataset. Only the address line 2 has missing values and we can ignore this for now since it is very common that customers only have address one or ignored supplying an alternative address.

> The datatypes were checked and correctly assigned. The sales datasets contains 4 numerical columns while other columns are categorical/object columns. 


## Summary of Findings

 > 92.70% of our sales counts are in shipped status. 
 > The top 5 countries by order count are USA, Spain, France, Australia and UK. 
 > In terms of count of orders classic cars, Vintage Cars and Motorcycles seems to be our hottest products.
 > Our Medium deal size is the best sold deal in terms of count of orders, even though it doesn't have much significant difference compared to the small deal size. We also explore this further too to see how revenue performance matches up to this deal sizes.
 > Our sales trend is very dynamic. We have discovered countries where we had the highest number of sales did not translate to the highest number of revenue for the company. Our Large deal size has also being the highest revenue stream while the medium size only enjoyed the highest number of patronage.
 > We also discovered that 2005 has the highest sales value and there is a positive correlation between quantity ordered and actual sales value.
 > Disputed makes the highest of our sales revenue followed by On Hold and then shipped.
 > It can be concluded that quantity ordered, price of each product and MSRP are strongly positively correlated to sales value. An increase in any of this value can give us an increase in the sales value


## Key Insights for Presentation

##### SALES BY PRODUCT LINE
> Our earlier countplot showed classic cars, Vintage Cars and Motorcycles seems to be our hottest products. However after digging into our sales value by product line, we can conclude our top 3 product line by sales revenue are Classic Cars, Trucks & Buses and Motorcycles.

> Classic cars retain its title of being the best sold, same with Motorcycles being third. However, Trucks and Buses is the second best sold product line in terms of revenue/sales value.

##### MONTH ON MONTH COMPARISON OF SALES FOR THE 3 YEARS
> Earlier we discovered 2005 seems to be the highest in terms of revenue from sales. It interested us to further drill this down by months for each year. From our further exploration of month on month comparison by year, 2005 Sales data is as at May 2005. It is interesting to discover only the first 5months of 2005 actually produced the highest revenue for the 3years. It seems we are doing something better and the year looks very bright for the business.

##### CORRELATION HEATMAP SHOWING IMPORTANT SALES VARIABLES
> The question we attempted to answer is , What are the variables that drive sales value?

> We used correlation to check this. Correlation closer to 1 means positive correlation, close to -1 means negative correlation and zero means no correlation while values close to zero means weak correlation

> We can conclude that quantity ordered, price of each product and MSRP are strongly positively correlated to sales value. An increase in any of this value can give us an increase in the sales value