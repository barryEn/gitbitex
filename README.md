This is an cryptocurrency exchange.

## Dependencies
* MySql (**BINLOG[ROW format]** enabled)
* Kafka
* Redis

## Install
### Server
* git clone https://github.com/barryEn/barryEn-spot.git
* Create database and make sure **BINLOG[ROW format]** enabled
* Execute ddl.sql
* Modify conf.json
* Run go build
* Run ./barryEn-spot
### Web
* git clone https://github.com/barryEn/barryEn-web.git
* Run `npm install`
* Run `npm start`
* Run `npm run build` to build production

