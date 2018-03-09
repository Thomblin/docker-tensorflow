# docker-tensorflow

basic tensorflow container with updates

# find at docker hub
  
https://hub.docker.com/r/thomblin/tensorflow/

    docker pull thomblin/tensorflow

    docker run -it -v $(pwd):/notebooks/src thomblin/tensorflow bash
    docker run -it -p 8888:8888 -v $(pwd):/notebooks/src thomblin/tensorflow jupyter notebook
