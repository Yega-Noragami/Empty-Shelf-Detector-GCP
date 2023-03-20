# Empty-Shelf-Detector-GCP


# How to use it

### Setup
build Docker image with the help of docker build 
For Mac:
```
docker build --platform linux/amd64 -t <image ID> -f Dockerfile .
```
Windows and linux:
```
docker build -t <image ID> -f Dockerfile .
```


After building the image you can run the image with the following command
```
docker run --name <image ID> -p 8000:8000 <image ID>
```

The option -p 80:80 exposes the Container port 80 as the Host port 80 to the world


### Goocle Cloud Platfrom Link :https://empty-space-hcgd2ilwsa-df.a.run.app/