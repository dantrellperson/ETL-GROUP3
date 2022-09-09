# ETL-GROUP3

Elite Transformers League, Unite!!


For this project, we were tasked with the challenge of extract, transforming and loading data. As a group, we decied that we would look at some of the housing demographics in the state of Georgia. We chose this data to assess the correlation between the average income and average hosuing costs across the state. We began with a csv file of zip codes that exist in GA. Our goal is was work with a this base zip code dataset and then extract different attributes/dimensions by zip codes, and then transform into JSON and load it into MongoDB.


Datasets Used: US Census Data and Atlanta Regional Commision
 - Dataset 01: https://gisdata.fultoncountyga.gov/search?tags=zip%20code
 - Dataset 02: https://data.neighborhoodnexus.org/
 


After we had decided on our datasets, we began working inside of Jupyter Notebooks to clean data by Panda & Python, as well as load dataset into Postgres. Then, extract all the data merge and loading it into MongoDB.

![posgresDB_income_table (1)](https://user-images.githubusercontent.com/107006423/189247984-a0a2e85a-76a7-4a99-a42e-4b0a013824d8.png)
 
-001 ![ERD](Income_table001.JPG)
-002 ![Income_table001](https://user-images.githubusercontent.com/30300016/189247499-1f91617f-1d79-4558-a277-e0b52326c55b.JPG)
-003 <img src="database_screen_shot/Income_table001.JPG"width="500">

- ![prosgresDB_population_table](https://user-images.githubusercontent.com/107006423/189239698-92aaf650-70a9-43f4-a45f-c6e6ca59e023.png)

- ![Screen Shot 2022-09-08 at 6 54 11 PM](https://user-images.githubusercontent.com/107006423/189240045-892b2515-0697-4c38-964f-80337efaca77.png)

- ![mongoDB (1)](https://user-images.githubusercontent.com/107006423/189240253-d2ed274c-c699-487e-a4bd-93892828f369.png)

