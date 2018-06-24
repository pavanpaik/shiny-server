# Shiny-Server
This is a docker version of Shiny Server.

## Build and Publish

### Build image
```
docker build -t pavanpaik/shiny-server .
```

### Publish image
Note: After running below command, you can access shiny-server using http://localhost:3838/
```
docker login
docker tag pavanpaik/shiny-server pavanpaik/shiny-server:1.00 
docker push pavanpaik/shiny-server:1.00 
```