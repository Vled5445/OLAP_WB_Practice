# OLAP_WB_Practice

Задание 1:

Clickhouse:

docker pull clickhouse/clickhouse-server

docker run -d  --cpus="1.5" --restart=unless-stopped -p 8123:8123 -v volume:/Users/vladpodsadnyj/docker/ clickhouse/clickhouse-server

docker restart e07d0ed2c2af 

docker stop  e07d0ed2c2af

docker rm e07d0ed2c2af   




Postgres:

docker pull postgres   

docker run -d  --cpus="1" --restart=unless-stopped -p 8888:8888 -v volume:/Users/vladpodsadnyj/docker/ postgres

docker restart 96a3c5c693d3

docker stop 96a3c5c693d3   

docker rm 96a3c5c693d3
