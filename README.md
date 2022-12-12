# [Real Industry Projects] Book-Rental-Recommendation
DESCRIPTION

Book Rent is the largest online and offline book rental chain in Australia. They provide books of various genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. 

Project Objective:

I, as an ML expert, had to focus on improving the user experience by personalizing it to the user's needs. I had to model a recommendation engine so that users get recommendations for books based on the behavior of similar users. This ensured that users are renting the books based on their tastes and traits.

Note: I performed user-based collaborative filtering and item-based collaborative filtering.

Dataset description:

BX-Users: It contains the information of users.

user_id - These have been anonymized and mapped to integers

Location - Demographic data is provided

Age - Demographic data is provided

If available, otherwise, these fields contain NULL-values.

 

BX-Books: 

isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from the dataset.

book_title

book_author

year_of_publication

publisher


 

BX-Book-Ratings: Contains the book rating information. 

user_id

isbn

rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.

 

I performed the following operations:

1- I have read the books dataset and explored it

2- I cleaned up NaN values

3- I read the data where ratings are given by users

4- I took a quick look at the number of unique users and books

5- I converted ISBN variables to numeric numbers in the correct order

6- I converted the user_id variable to numeric numbers in the correct order

7- I converted both user_id and ISBN to the ordered list, i.e., from 0...n-1

8- I re-indexed the columns to build a matrix

9- I split my data into two sets (training and testing)

10- I made predictions based on user and item variables

11- And I used RMSE to evaluate the predictions
