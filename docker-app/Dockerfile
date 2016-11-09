FROM ubuntu:5001/docker-framework:latest

MAINTAINER Jon Roquelaure jonathanr@jfrog.com

COPY ui/frogsui /home/exec/frogsui/
ADD jar/*.jar /home/exec/frogsws.jar

CMD java -jar /home/exec/frogsws.jar