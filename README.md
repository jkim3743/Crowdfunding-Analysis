#Kickstart My Chart

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this assignment, I organized and analyzed a database of 4,000 past projects in order to uncover any hidden trends.

<img width="2827" alt="FullTable" src="https://user-images.githubusercontent.com/11654374/132019403-0189d005-7195-4750-8d5a-2f4ce8b5fcf8.png">

* Used conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

 <img width="1011" alt="CategoryStats" src="https://user-images.githubusercontent.com/11654374/132019546-0fbaf60a-e39b-48ed-8601-e9129a47ddb8.png">

  * Created a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category**.

  * Created a stacked column pivot chart that can be filtered by country based on the table you have created.


 <img width="807" alt="SubcategoryStats" src="https://user-images.githubusercontent.com/11654374/132019666-44e77f48-4521-42fa-a253-c44505060649.png">

  * Created a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.

  * Created a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.



![5](https://user-images.githubusercontent.com/11654374/132020240-49aeb0c8-6cd9-4a4e-b8d9-c935ea11f7ad.png)

* Created a new sheet with 8 columns:

  * `Goal`
  * `Number Successful`
  * `Number Failed`
  * `Number Canceled`
  * `Total Projects`
  * `Percentage Successful`
  * `Percentage Failed`
  * `Percentage Canceled`

* In the `Goal` column, create 12 rows with the following headers:

  * Less than 1000
  * 1000 to 4999
  * 5000 to 9999
  * 10000 to 14999
  * 15000 to 19999
  * 20000 to 24999
  * 25000 to 29999
  * 30000 to 34999
  * 35000 to 39999
  * 40000 to 44999
  * 45000 to 49999
  * Greater than or equal to 50000

