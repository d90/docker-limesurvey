# docker-limesurvey

LimeSurvey
==========

LimeSurvey - the most popular
Free Open Source Software survey tool on the web.

https://www.limesurvey.org/en/

This docker image easies limesurvey installation specifically for connecting to TSQL (mssql). This will not connect to postgres or mysql. 

## Usage

To run limesurvey on port 80 just:

    docker pull nd90/docker-limesurvey:latest
   
    docker create \
    --name limesurvey \
    -p 80:80 \
    nd90/docker-limesurvey:latest


