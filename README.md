This is a Book Recommendation System.

data sets are used from the GoodReads  link > https://mengtingwan.github.io/data/goodreads.html
from the website, you need to download 2 datasets for this project.

1. goodreads_books.json.gz ( for now it is of size 2GB)  This is available under the meta-data of books
2. goodreads_reviews_dedup.json.gz ( for now it is of size 5 GB) This is available under the Book reviews

this system is built by using these techniques:

1) Basic cut
     > Top 50 books with best book_average_rating
     > Top 50 concised books
     > Top 50 e-books
     > Books having similar book title
     > Books having similar description
     > Books that got similar review
     > Books where user choice's match
     > 
2) Similar cover-page of books

3) Correlation-based recommender system

4) Content-based Filtering

5) Collaborative Filtering
   > memory based
   > model based
   

