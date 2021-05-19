# ROSSMANN REGRESSION PREDICT

Link to the telegram bot: http://t.me/pre_ross_bot

![houses prices analytics](/home/valcilio/Downloads/REGRESSION PREDICT.png)

**PREMISES:**

This project has as premise to help the company "Rossmann Store Sales", to predict its sales in the next six weeks.

Rossmann asked one main question:

1. What will be the sales value of each of my stores in the next six weeks and I can visualizate the results in my cellphone?

Then this project uses the 'XGBoost Regression' algorithm to solve this question and the telegram to make a bot to tell the results per store.

**Attributes List:**

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

**Solution Plan:**

The plan to solute this business problem was make a study about the best machine learning regression model to implement and make the prediction. With the prediction made about the sales of the next six weeks was make a bot in th telegram to tell the results to the CEO on his cellphone.

**Financial Results**

With the results of the prediction is expected that the CEO be able to make the correct decisions about the stock allocated on each store and the marketing where invest more in marketing. Besides that, is expected that the CEO be able to predict the real value of gross revenue expected.

This can be able to increase the financial gains until 50% because this can help the Rossmann to save money and increase the gross revenue through the correct allocation resources.

**Next Steps**

As next steps is expected to continue to feed the model to predict the next times week's sales and make a analysis about the results obtained with the prediction provided by the model to define the real gains with him. Besides that, is expected that is gettered more dates about the marketing and the store's design to increase the accuracy of the prediction and generate more value. 

**Conclusion**

Rossmann will be able to make a better preparation with the data obtained through being capable to reduce the expenses and increase the revenue.