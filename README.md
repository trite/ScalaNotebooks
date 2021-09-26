Learning scala, using jupyter notebooks to follow along while reading Functional Programming, Simplified (Scala edition) 

Map whatever directory this is cloned into as the home path for the jovyan user in this docker container:
```
docker run -d -p 8888:8888 -v C:\stuff\docker\all-spark-notebook\:/home/jovyan jupyter/all-spark-notebook
```
