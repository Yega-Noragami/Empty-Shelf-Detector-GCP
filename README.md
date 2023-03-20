# Empty-Shelf-Detector-GCP

This project is a proof-of-concept implementation of an Empty Shelf Detection system using computer vision techniques. The system is capable of detecting empty shelves in a retail environment and alerting store employees to restock the shelves.

The project includes a Docker app that can be deployed to Google Cloud Platform, making it easy to run and manage the system at scale. The app includes a pre-trained deep learning model that can quickly detect empty shelves in real-time video feeds.


# Demo Example 
![Empty Shelf Example](https://github.com/Yega-Noragami/Empty-Shelf-Detector-GCP/blob/main/indedx.jpeg)

# How to use it

To get started with the Empty Shelf Detection system, you will need to:

- Clone the GitHub repository to your local machine.
- Install Docker on your local machine (if not already installed).

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

- Build the Docker image using the provided Dockerfile.

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

- Deploy the Docker image to Google Cloud Platform.
After building the image you can run the image with the following command
```
docker run --name <image ID> -p 8000:8000 <image ID>
```

The option -p 80:80 exposes the Container port 80 as the Host port 80 to the world


### Goocle Cloud Platfrom Link :https://empty-space-hcgd2ilwsa-df.a.run.app/

Once the system is up and running, you can start testing it out by pointing a video feed at a retail shelf and observing the results.

#Contributions 

We welcome contributions from anyone interested in improving the Empty Shelf Detection system. If you'd like to get involved

