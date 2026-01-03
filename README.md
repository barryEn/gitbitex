This is an cryptocurrency exchange.

## Dependencies
* MySql (**BINLOG[ROW format]** enabled)
* Kafka
* Redis

## Install
### Server
* git clone [https://github.com/barryEn/barryEn-spot.git](https://github.com/barryEn/gitbitex.git)
* Create database and make sure **BINLOG[ROW format]** enabled
* Execute ddl.sql
* Modify conf.json
* Run go build
* Run ./barryEn-spot


