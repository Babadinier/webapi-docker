# .net 5 web api with docker file

## Build dockerfile 
- docker build -t {name-image} .

## Run docker image 
- docker run -d -p 8080:80 --name {name-container} {name-image}