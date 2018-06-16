# Simple TCP Client Server

## Clone the repository

```
$ git clone https://github.com/alexlargacha/server_client_tcp.git
```

## Basic Build

Run the following commands to build the server and the Client
```
$ cd server_client_tcp
$ gcc ClientTCP.c -o ClientTCP
$ gcc ServerTCP.c -o ServerTCP
```

## Run the example

```
$ ./ServerTCP &
$ ./ClientTCP 127.0.0.1 "Hello World"
```
