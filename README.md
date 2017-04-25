# docker-limesurvey

LimeSurvey
==========

LimeSurvey - the most popular
Free Open Source Software survey tool on the web.

https://www.limesurvey.org/en/

This docker image easies limesurvey installation. Includes libs for MSSQL connection and FreeTDS. 

## Usage

To run limesurvey in 80 port just:

    docker pull nd90/docker-limesurvey:latest
   
    docker create \
    --name limesurvey \
    -p 80:80 \
    -v
    nd90/docker-limesurvey:latest
