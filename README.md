# Simple TCP Client

## Clone the repository

```
$ git clone https://github.com/alexlargacha/server_client_tcp.git
```

## Basic Build

Run the following commands to build the App
```
$ docker build -f Dockerfile.TwoStage -t <image_tag>:latest .
```

## Run the example

```
$ docker run -it <image_tag> <server_ip> "some text"
```
