# docker:
docker build -t pokealarm .

# Start locally
docker run --name pokealarm pokealarm -cf config/config.ini

# To Deploy on Heroku
heroku container:push web