# Charity_Use_Case_Challenge



The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With  knowledge of machine learning and neural networks, I'm using the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


First step is preparing the data: 

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

    EIN and NAME—Identification columns
    APPLICATION_TYPE—Alphabet Soup application type
    AFFILIATION—Affiliated sector of industry
    CLASSIFICATION—Government organization classification
    USE_CASE—Use case for funding
    ORGANIZATION—Organization type
    STATUS—Active status
    INCOME_AMT—Income classification
    SPECIAL_CONSIDERATIONS—Special considerations for application
    ASK_AMT—Funding amount requested
    IS_SUCCESSFUL—Was the money used effectively

Shown below is the number of values found in each of the columns: 

![Screenshot 2024-02-26 at 9 25 18 PM](https://github.com/davisdw/Charity_Use_Case_Challenge/assets/104311388/c88806fa-cccd-4fda-9857-1179c5299a80)


Next is to create binning for values that is considerable small outliers and have them group and assign as Other category: In this case Application Type and Classification is utilized 

![Screenshot 2024-02-26 at 9 26 25 PM](https://github.com/davisdw/Charity_Use_Case_Challenge/assets/104311388/6bfc420f-bc96-4a0d-b6fc-b57616bd36e2)



![Screenshot 2024-02-26 at 9 26 01 PM](https://github.com/davisdw/Charity_Use_Case_Challenge/assets/104311388/56d855c2-4971-45cf-848f-11f64b833028)




