
## How to Use 

1- Build the Docker image : 
```docker
docker build . -t python-app
```

2- Run the Docker image : 
```docker 
docker run -p 3000:5000 python-app
```

3- Open http://localhost:3000 in your browser to use the application.