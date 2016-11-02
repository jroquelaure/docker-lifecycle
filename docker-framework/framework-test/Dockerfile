FROM 10.5.24.29:5001/docker-framework:latest

MAINTAINER Jon Roquelaure jonathanr@jfrog.com

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
