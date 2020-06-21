# tig-stack

Docker compose for influxdb with telegraf to fetch data from the things network.


## Setup

Copy `influxdb/influxdb.env.examle` to `influxdb/influxdb.env` to configure influxdb

Copy `telegraf/telegraf.conf.example` to `telegraf/telegraf.conf.example` then configure telegraf

Run `docker-compose up -d` to start containers and setup network.
