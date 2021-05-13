# Simple Rest Api with Golang and MySql
Simple Rest Api with Golang and MySql

Another dependencies included :
- github.com/gorilla/mux 
- github.com/go-sql-driver/mysql 
- github.com/joho/godotenv 

Installation :
1. Run ```git clone https://github.com/nubbdev/go-rest-api.git```
2. Run ```go get github.com/gorilla/mux```
3. Run ```go get github.com/go-sql-driver/mysql```
4. Run ```go get github.com/joho/godotenv```
5. Create local database and run query below
```
CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(50) NOT NULL DEFAULT '0',
  `last_name` varchar(50) NOT NULL DEFAULT '0',
  PRIMARY KEY (`id`)
)
```
6. Update .env config files and fill in with your environtment database
7. Run command below (your position should in the clone directory)
```
go build
```
wait until go building executable app, then
```
. ./yourAppName
```
Don't forget to create row of the ```users``` database. Happy coding ༼ つ ◕_◕ ༽つ
