docker compose up -d
docker compose down
docker exec -i be_da_241_cnpm-DA241-mysql-1 mysql -uroot -p123456 DA241_DB < src/config/data.sql
docker exec -it be_da_241_cnpm-DA241-mysql-1 mysql -u root -p

### Install Packages 
`npm install express dotenv jsonwebtoken cors cookie-parser`

### Config DATABASE
Config `.env` file for available with database schema (DB Server)
Use `MySQL` to connect DataBase
Run SQL in `data.sql` for adding initial data

### Run BackEnd Server
`npm start`

### Test API
Using `Post Man` or `Thunder Client`
