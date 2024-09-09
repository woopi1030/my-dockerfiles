## docker build
docker build -t mysql_image .

## container start
docker run -d --name local_mysql -p 13306:3306 --restart=always mysql_image