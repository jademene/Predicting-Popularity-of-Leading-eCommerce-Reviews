# Predicting the Popularity of Leading eCommerce's Reviews
This project looks into an eCommerce site's product reviews to predict the popularity of a review to manage potential popular negative feedback. This is important to the client as they are known to always monitor client satisfaction.
### Goal:
Study the characteristics that made a review popular to design an early intervention in case of potential popular negative feedback.
### Business Decisions:
* Computation speed will be improved where possible to keep running costs down while maintaining performance.
* Scalability of the final solution is preferred to accommodate the ever-growing nature of the business.
### Limitations:
This project will explore the task as a regression problem, and as such, other modelling options will not be explored.
* The data has been provided with limited context knowledge about the variables.
* The data might have already been pre-processed; this information is not available to us.
### Data Collection
The data were collected during a survey analysis of site clients to predict user satisfaction levels. The initial analysis found that user satisfaction levels are driven by popular product reviews (popularity = high no. likes).
#### Dataset Description
There are a total of 38,000 records divided into two datasets:
* model.csv: This dataset contains the information of 28,000 reviews with the respective target variable (column named "shares").
* predictions.csv: This dataset contains the information of 10,000 reviews without the target variable. We are requested to provide the predictions for this set of records.

_Note: this was a collaborative task with a fellow classmate in the international BABD master @ POLIMI General School of Management._
