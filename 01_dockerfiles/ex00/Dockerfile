FROM alpine

RUN apk update && apk upgrade && apk add vim

ENTRYPOINT ["vim"]

# docker build --tag okuzniet/vimapp ~/docker/01_dockerfiles/ex00
# docker run -it --rm okuzniet/vimapp

#docker build --help

#For dockerfiles you will need to build the image first
#docker build -t [container name] [/path/to/Dockerfile]
#You then run the container (with right flags for each exercise)
#docker run [--interactive] [--tty] [container name]