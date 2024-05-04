# YouTube Data API Comments

A Dataset of Comments from YouTube Movie Trailers created using the YouTube Data API.

## File Info

* [CollectTrailerIDs.ipynb](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/DataScraping.ipynb)
  * Collected video IDs from YouTube movie trailers using the Search method of the YouTube Data API.

* [CollectComments.ipynb](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/DataCleaning.ipynb)

  * Collected comments from YouTube movie trailers using the CommentThreads method of the YouTube Data API.
  
    * Some movies returned 0 comments because the comments were turned off.

* [FixErrors.ipynb](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/DatasetCreation.ipynb)
  * Collected comments for movies that had 0 Comments.

* [WikipediaMovieDatasetWithTrailerIDs.csv](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/WikipediaMovieDatasetFinalNew.csv)
  * Dataset of movie infos including YouTube video IDs for trailers. 
 
* [MovieTitleTrailerID.csv](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/WikipediaMovieDatasetFinalNew.csv)
  * A dataset with just the movie titles and video IDs for trailers.

* [MovieCommentsWithFailures.csv](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/WikipediaMovieDatasetFinalNew.csv)
  * A dataset of movie comments **including** those titles that returned 0 comments.

* [MovieComments.csv](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/WikipediaMovieDatasetFinalNew.csv)
  *  A dataset of movie comments **excluding** those titles that returned 0 comments.

* [MovieFailures.csv](https://github.com/tasinms/YouTube-Data-API-Comments/blob/master/WikipediaMovieDatasetFinalNew.csv)
  * A dataset of movie titles that returned 0 comments.

<br />

<br />

<br />

<img align="right" src="https://i.imgur.com/vFb1T8l.png" alt="Logo" style="width:200px;">
