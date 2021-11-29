# colabcont

A Docker container to act as a local runtime for [Google Colab](https://colab.research.google.com).

colabcont is a container image providing a local runtime for colab computations. 

## Run
```bash
$ docker run -it --rm -p 8081:8081 movq/colabcont:dev
```

## Connecting

In colab select a local runtime as executor. You will need Chrome or Firefox and WebSocket support enabled. 
Then use the URL and the token provided in the container run as connection settings. 

