#FROM alpine
#FROM openjdk:8-jdk-alpine3.9

FROM ubuntu
RUN apt update
RUN apt install -y openjdk-17-jdk
WORKDIR /myapp
copy HelloWorld.class .
cmd java HelloWorld