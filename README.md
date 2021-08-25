# Introduction-to-Docker

## Run the Docker container locally

1. Clone the repository:

```
git clone https://github.com/Seris370/Introduction-to-Docker
```

2. Build the image:

```
docker build -t webserver .
```

3. Run the container:

```
docker run -p 80:80 --rm -d --name nginx_reverse_proxy webserver
```
