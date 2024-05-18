# Charmr main website
Build the container
```shell
docker build -t charmr:v1 .
```
Run the container
```shell
docker run -d -p 8080:80 charmr:v1
```
Access the site

http://127.0.0.1:8080/

test