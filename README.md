# [Real Industry Projects] Book-Rental-Recommendation

I, as an ML expert, focused on improving the user experience of Book Rent, the largest online and offline book rental chain in Australia, by personalizing it to the user's needs. My goal was to model a recommendation engine so that users would get recommendations for books based on the behavior of similar users. This would ensure that users were renting books based on their tastes and preferences, which would ultimately increase the company's revenue and profit.

To achieve this goal, I used the BX-Users, BX-Books, and BX-Book-Ratings datasets. I read and explored the books dataset, cleaned up any NaN values, and took a quick look at the number of unique users and books. I then converted the ISBN and user_id variables to numeric numbers in the correct order and re-indexed the columns to build a matrix.

Next, I split my data into two sets (training and testing) and made predictions based on user and item variables. I then used the Root Mean Squared Error (RMSE) to evaluate the predictions.
