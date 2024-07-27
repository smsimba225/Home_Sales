# Home_Sales

This was an interesting exercise concerning Big Data. It was very interesting to see how the query times changed based on how the data was stored. Compared to simply running queries on a csv, caching the data, as well as converting data into a parquet dramatically reduced the time required to run the same queries.  By reducing the query run times, the cost for anyone needing to store and access the data will edramatically reduced.  Not only does the run time get reduced, the size of the data would be much smaller as well.  

It would be interesting to note whether the cached version or the parquet version will be faster.  In this exercise, the cached version was the fastest, but this may change for a much larger data set, especially if the parquet version stores the data in a different fashion.

Thank you for looking at my work!
