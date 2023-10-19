# Snowpipe
Automatically move data from AWS S3 to Snowflake datawarehouse with snowpipe.

## Pipeline explanation
We have to set up an **event notification** in the S3 bucket to sent to the pipeline
so that every time a new file gets uploaded, the data / files get moved **automatically** to the data warehouse.
![snowpipe_image](https://github.com/dominicho97/Snowpipe/assets/43000003/be42a51c-517e-4daa-819e-6a2f11a5405e)


### Pipeline
![pipe](https://github.com/dominicho97/Snowpipe/assets/43000003/70be516e-cac7-482d-a269-4bd9c06df011)

### Pipeline check
![snowpipe_status_check](https://github.com/dominicho97/Snowpipe/assets/43000003/47cfeacb-8c62-4863-a712-a46ee9281a9a)

### Pipeline / notification check
![snowpipe_state](https://github.com/dominicho97/Snowpipe/assets/43000003/67aada0d-c308-460a-9f4c-b08889fa967f)
