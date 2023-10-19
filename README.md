# Snowpipe
Automatically move data from AWS S3 to Snowflake datawarehouse with snowpipe.

## Pipeline
We have to set up an **event notification** in the S3 bucket to sent to the pipeline<br>
So that every time a new file gets uploaded, the data / files get moved **automatically** to the data warehouse.
![snowpipe_image](https://github.com/dominicho97/Snowpipe/assets/43000003/be42a51c-517e-4daa-819e-6a2f11a5405e)
