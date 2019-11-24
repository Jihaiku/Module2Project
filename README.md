# Northwind-Trader-s-Dataset-Analysis

I will be using the [dataset](https://relational.fit.cvut.cz/dataset/Northwind) provided from here to create questions that I can assist with through data science as well as answer the single question we were provided.

![Northwind_ERD](https://user-images.githubusercontent.com/48660919/69501810-811a5c00-0ed6-11ea-977d-b27c8ffce809.png)

# Goals

Below are the four questions we were given as well as visualizations and answers for them.

## Question Provided

Do discounts have a statistically significant effect on the number of products customers order? If so, at what level(s) of discount?

![Q0 Graph](https://user-images.githubusercontent.com/48660919/69501809-7e1f6b80-0ed6-11ea-9926-f9d2c1dac2db.PNG)

Based on the very strong P value through multiple tests based on the Quantity of items sold given Discount rates I think that all of the levels of discounts up to 0.25 cannot be proven as false therefore they hold siginficance. So we reject the Null. There are no statistical difference when the coupons are used.

## Question 1

Does the average price in the purchase hold statistical sifnificance towards the category of goods purchased?

![Q1 Graph for real](https://user-images.githubusercontent.com/48660919/69501812-84154c80-0ed6-11ea-863b-ab86c33d3ef8.PNG)


![Q1 Graph](https://user-images.githubusercontent.com/48660919/69501813-84154c80-0ed6-11ea-8486-fe12187d8825.PNG)

While it would have been more helpful to check the discount rate with relation to total price for each category there just wasn't enough data to have a very valid test. In fact if there was something that I could expand on the number of samples would be that so we could do a more in depth search for this data.

However, for the companies what this data tells us is that most of the categories hold some significant value when compared to each other. If we are to dive further on this and check discounts per category further data collection is necessary.

## Question 2

Is there a statistical significance for total revenue per region?

Each of the regions hold a decent amount of significance when compared this way, there would be no reason to fully invest in one region over the other unless we further dug into the data with more data acquisition to see which specific regions that were not large enough on their own to sample are worth continuing sales with.

## Question 3

Is there a statistical significance on Average Price based on who is shipping it?

![Q2 Graph](https://user-images.githubusercontent.com/48660919/69501814-84154c80-0ed6-11ea-999a-e1a14ffecfb6.PNG)

I think that this data tells us that each of the shipping companies is worth using but we must re-evaluate the question if we wish to go further into this for the sellers. One thing that we could do is check the significance of each shipper based in each region to see which ones do better and hold signfiicance but we don't have enough data to check each region.

# Conlusion

Between the four questions that were sorted out and asked today we had learned quite a bit about the statistical significance between related data.

If we were to continue our search to make or refine this information I think the biggest aspect would be having more data points in general since there were questions relating to categories significance based on each level of discount but there was just not enough data per point to make a reasonably sized sample to do any tests on.

And to reitterate what the questions have taught us:

* Discounts yield significant results when based on Quantity

* Average price does yield significant results when based on type of Item bought

* Futher research is required to make this data better

* Average price yield a signficant results when based on Region

* We can reject the Null hypothesis in somes cases however.

* Average price yield a signficant results when based on Region

* We can reject the Null hypothesis in somes cases however.

# Contact

If you have any questions please contact me and we can discuss them.

Thank you for checking out my project and have a great day!
