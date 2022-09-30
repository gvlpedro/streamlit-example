

# Build

``` 
docker build -t streamlit .
```

```
docker run -p 8501:8501 streamlit
```



# Clean docker images


## To stop all Docker containers

```
docker kill $(docker ps -q)
```

## To remove all Docker Containers

```
docker rm $(docker ps -a -q)
```


## To remove all Docker images, run this command:

```
docker rmi $(docker images -q)

``
