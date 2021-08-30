## run jupyter pyspark docker img:
```
docker run -it --rm -p 8888:8888 -v ./notebooks:/home/jovyan/work jupyter/pyspark-notebook
```
or
```
docker compose up -d
```

## Start notebook

http://localhost:8888/?token=e144d004f6652ae6406a78adf894621e62fdeb1fc57d02e8