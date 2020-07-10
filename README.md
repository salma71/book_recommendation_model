# Book Recommendation model

Building a model to recommend books based on user-based and item-based collaborative filtering approaches

## Future work

1. I used only the accuracy based metric RMSE; however, many other metric could be used like @MAP, @recall...etc.
2. We can convert back the ISBN_Index into the original ISBN string in the recommendation object, then we can join with the books table and get book recomendation by book title.
3. We can use the users, books, and rating tables to build a recommender model using RNN - next step for me. 
4. A content-based recommendation model could be built using bookTitle and do even more by expanding it and hypertune it.  


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)