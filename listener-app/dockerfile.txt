# Pull base image
From rossbachp/apache-tomcat8

# Maintainer
MAINTAINER "Disney <demo2poc@disney.com">

# Copy to images tomcat path
COPY listener-app.war /opt/tomcat/webapps/
COPY logging-listener-app.war /opt/tomcat/webapps/
#COPY listenerapp-config.properties /opt/tomcat/lib/

#Step1:sudo docker build -t listenerapp:2 /tmp/docker_demo2/listenerapp_docker
#Step2:sudo docker run -d -p 8080:8080 listenerapp:2 or  docker run -it --rm -p 8080:8080 listenerapp:2
#Step3:sudo docker exec -it <containerid> /bin/bash



