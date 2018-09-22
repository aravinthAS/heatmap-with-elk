# Heatmap with elk

## Run Elk stack on docker
To run something on docker, make sure that you have installed docker already.
Run docker and run this command:
```
sudo docker pull sebp/elk
```
and then run this,
```
sudo docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk sebp/elk
```
