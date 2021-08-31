# speedtest-suite
based on https://dev.to/elalemanyo/how-to-install-docker-and-docker-compose-on-raspberry-pi-1mo  
  
## how to run
./start.sh  
./stop.sh  
  
## additional command
docker-compose up  
docker-compose down  
docker-compose ps --services  

## additional info
for grafana, default username is admin, default password is admin  
  
## grafana config for influx
HTTP.url = <ip-address>:8086  
HTTP.access = server  
  
Database = speedtest  
User = admin  
Password = password  
