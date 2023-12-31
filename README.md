# Spotify-ETL-pipeline

This project showcases a comprehensive data engineering pipeline built on the Spotify API. 
* It involves seamless integration with the Spotify API to extract data and utilizes AWS Lambda for automated extraction.
* To ensure regular data extraction, a scheduled-trigger using AWS CloudWatch is implemented.
* The extracted data is then transformed by applying custom transformations written in Python within the Lambda function.
* The transformation process is automated by adding an S3 trigger.
* The transformed data is securely stored in S3.
* For efficient data analysis, analytics tables are created using AWS Glue and Athena.
* Additionally, the project utilizes the spotipy_layer, an added layer in AWS Lambda, to access the spotipy library for enhanced functionality.
