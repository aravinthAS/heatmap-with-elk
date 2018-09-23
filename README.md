# Heatmap with elk

## Run Elk on docker
To run something on docker, make sure that you have installed docker already.
Run docker and run this command:
```
sudo docker pull sebp/elk
```
and then run this,
```
sudo docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk sebp/elk
```

## Kibana
Use this url below to get user interface:
```
http://localhost:5601
```

## Put data with logstash to elk
```
cat test.csv | logstash -f geostore.conf
```

# Link
https://www.viaboxx.com/code/easily-generate-live-heatmaps-for-geolocations-with-elk/#codesyntax_1
