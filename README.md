# ROSSMANN REGRESSION PREDICT

Link to the telegram bot: http://t.me/ross_pred_bot

![houses prices analytics](https://i.ibb.co/Tg5Dfxy/ross-regression.png)

## **PREMISES:**

Rossmann owns a network of stores across the United States and, as such, has its stock as its greatest asset.

However, as the number of stores is very high and their stock is basically bought and then resold, they need to be very careful with the amount of products they buy to prevent there being an unnecessarily large cost of goods sold.

Currently, as the sales prediction is done by an excel spreadsheet in the average model, they end up having a loss of up to 30% of their gross stock due to spoiled products and some stores always have a loss of up to 50% of customers due lack of stock at certain times.

***The Rossmann people came to the conclusion that with these metrics it is possible to increase the company's profits by up to 40% if they can allocate the inventory correctly, as this would save a good part of the wasted money, while at the same time they could supply the stores that could come running out of stock.***

A meeting was held with Rossmann's managers, directors and the CEO where they decided to plan how the distribution of stock for the next month and a half would be done.

However, they were unable to reach a satisfactory conclusion, as everyone thought something different, in order to reach a consensus they then opted to consult the company's data scientists, as they would have unbiased and factual information since they would use data and not opinions based on personal experience.

Thus, after asking questions such as: "Why do you want to know the ideal stock for?"

The conclusion was reached that what they really want to know is when they should invest in each store's inventory so that they don't have more inventory than they would actually sell.

Then the business question is: **"How much each store will sell in the next six weeks?"**

## **Attributes List:**

| Attributtes                      | Meaning                                                      |
| -------------------------------- | ------------------------------------------------------------ |
| Id                               | an Id that represents a (Store, Date) duple within the test set |
| Store                            | a unique Id for each store                                   |
| Sales                            | the turnover for any given day (this is what you are predicting) |
| Customers                        | the number of customers on a given day                       |
| Open                             | Num of bathrooan indicator for whether the store was open: 0 = closed, 1 = openms |
| StateHoliday                     | indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None |
| SchoolHoliday                    | indicates if the (Store, Date) was affected by the closure of public schools |
| StoreType                        | differentiates between 4 different store models: a, b, c, d  |
| Assortment                       | describes an assortment level: a = basic, b = extra, c = extended |
| CompetitionDistance              | distance in meters to the nearest competitor store           |
| CompetitionOpenSince[Month/Year] | gives the approximate year and month of the time the nearest competitor was opened. |
| Promo                            | Indicate the quality of the house on grafic design.          |
| Promo2                           | Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating |
| Promo2Since[Year/Week]           | describes the year and calendar week when the store started participating in Promo2 |
| PromoInterval                    | describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store |

## **Solution Plan:**

Defined that what they need is a sales forecast for the next six weeks per store so the attitudes to be considered in response were defined:

**1 -** Gain understanding of the data through a statistical and exploratory analysis of the data and also derive new columns of data.

**2 -** Validation of business hypotheses to produce insights and manual selection of columns to be used that will add to the selection via algorithm.

**3 -** Preparation of data for model training and model selection.

**4 -** Selection of the best model parameters through the random search method.

**5 -** Translation and interpretation of the error to transform the model result into business value.

**6 -** Deployment of the model so that Rossmann's top leadership can access the results obtained at any time and be able to take decisions.

With all the solution planned the item to show in the end was designed to be:

- The accuracy of this model.
- One telegram bot to the business people access all the information.
- One video explaining the solution to the business people learn how use the solution.

## **Financial Results**

With the results of the prediction is expected that the CEO be able to make the correct decisions about the stock allocated on each store and the marketing where invest more in marketing. Besides that, is expected that the CEO be able to predict the real value of gross revenue expected.

This can be able to increase the financial gains until 50% because this can help the Rossmann to save money and increase the gross revenue through the correct allocation resources.

## **Next Steps**

As next steps is expected to continue to feed the model to predict the next times week's sales and make a analysis about the results obtained with the prediction provided by the model to define the real gains with him. Besides that, is expected that is gettered more dates about the marketing and the store's design to increase the accuracy of the prediction and generate more value. 

## **Conclusion**

On this way, Rossmann will be able to have a better use of its stock, increasing its profit by about 34% and enabling it to improve its decision making.

In addition, following the necessary next steps, it will be possible to further improve the model's accuracy by reducing its error, allowing for a brief increase in gross sales.
