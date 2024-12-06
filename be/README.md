docker compose up -d
docker compose down
docker exec -i be_da_241_cnpm-DA241-mysql-1 mysql -uroot -p123456 DA241_DB < src/config/data.sql
docker exec -it be_da_241_cnpm-DA241-mysql-1 mysql -u root -p

### Install Packages 
`npm install express dotenv jsonwebtoken cors cookie-parser`