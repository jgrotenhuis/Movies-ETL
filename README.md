# Movies-ETL

The goal of this challenge was to take the Jupyter notebook that we had made from the module and create a Python script with out the analysis/exploratory code blocks.  This automated ETL pipeline can now be used to import, transform, and load data from future data sets.  After reading through my code carefully, I think it's safe to make the following 5 assumptions:

1) I'm assuming there won't be any new alternative titles, since my clean_movie function includes only a list of 20 alternative titles.

2) I'm also assuming that there won't be any new column names that have already be merged together, such as when I merged "Produced by" & "Producer" with the column "Producer(s)".

3) Another assumption would be that certain data types are always convertible to int, object, string, etc.  This may not always work.

4) It's possible that in the future, there will be new rating systems with their own rubrics. A basic rubric of 1-5 could some day also include ratings like the Tomatometer by Rotten Tomatoes, or a numerical ratings system with a longer range (current 1-5 vs 1-100) in the future.

5) We would also need to add some flexibility for new data sources likes JSONs or CSV to be added in the future.

