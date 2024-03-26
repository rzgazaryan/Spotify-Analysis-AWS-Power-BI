# Spotify-Analysis-AWS-Power-BI
I compiled three separate datasets on artists, tracks, and albums from online sources and processed them using AWS Glue for ETL operations. After cleaning and joining the data, I stored it in an S3 bucket for final warehousing. Using AWS Glue's crawler, I transferred the prepared data to Athena, organizing it into one table. Following that, I ensured correct user permissions, installed an ODBC driver, and connected Power BI to Athena for visualization. The resulting report focuses on Spotify data, displaying the yearly release count of songs in the US, their average duration, and their relationship over time. Users can filter data by timeframe and season.


