
## How to Use 

1- Build the Docker image : 
```docker
docker build . -t vue-app
```

2- Run the Docker image : 
```docker 
docker run -p 9000:8080 vue-app
```

3- Open http://localhost:9000 in your browser to use the application.