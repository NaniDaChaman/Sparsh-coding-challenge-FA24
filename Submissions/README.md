# ⛵ Welcome to Sparsh's submission of  2024 EM/Dev Assessment! ⛵
## Project : Classification of Vanderbilt's Faculty Donations.
- This project trains a 5 Nearest Neighbors model to predict which political pacts/comittees do Vanderbilt Faculties Donate to
- this prediction is based on their contributed amount, their zip code, their work designation, their employers and the type of election that was being run.
- The data was derived from these sources :
  1. [Induvidual Contributors Lookup](https://www.fec.gov/introduction-campaign-finance/how-to-research-public-records/individual-contributions/)
  2. [Open Secrets](https://www.opensecrets.org/donor-lookup/results?cand=&cycle=&employ=Vanderbilt+University&jurisdiction=&name=&occupation=&order=desc&page=2&sort=D&state=&type=&zip=)
  3. [FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Vanderbilt+University&two_year_transaction_period=2020&two_year_transaction_period=2022&two_year_transaction_period=2024&min_date=01%2F01%2F2020&max_date=12%2F31%2F2024)
- Credit for consolidating this data goes to the Data Section of Vanderbilt Hustlers Staff; please check out their upcoming story on Vanderbilt Faculty Donations as well (which I will link to as soon as it comes out).
- My work can be found in the 3 pynb file which also can be opened in google colab
  
 ## Run our pynb
 - To run this open the notebook with the google colab link and choose Runtime>Run All
 - The output of this file would have to be downloaded and pushed into the repo separately as I could not share my token in google colab
   
  ## Political Dataset_cleaning.ipynb
  - This files cleans our orignal file Submissions/data/VandyDonations2024_2020.csv and produces the Submissions/data/donations_cleaned.csv
    
  ## Political_dataset_modeling.ipynb
  - This files processes Submissions/data/donations_cleaned.csv and produces the Submissions/data/donations_processed.csv
  - It labels our categorical data with numbers and also creates our 5nn model along with a PCA analysis showing why a nearest neighbor model was chosen
 
   ## Model_evaluation.ipynb
  - This file processes Submissions/data/donations_processed.csv to evaluate our model with precision and recall
  - Reason for choosing these metrics is shown as well
  - Room for improvement is discussed
 
   
