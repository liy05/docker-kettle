# docker-kettle

Pentaho Data Integration (PDI)

```
docker run -ti --name pdi -e KETTLE_USER=liyang -e KETTLE_GROUP=ETL \
    -v ~/.docker/kettle/user:/home/hive \
    -v ~/.docker/kettle/datas:/opt/pdi-ce/datas \
    -v ~/.docker/kettle/jobs:/opt/pdi-ce/jobs -d pdi:7.0
```
