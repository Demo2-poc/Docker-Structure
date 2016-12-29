# Pull base image
From rossbachp/apache-tomcat8

# Maintainer
MAINTAINER "Disney <demo2poc@disney.com">

# Copy to images tomcat path
COPY MDXWeb.war /opt/tomcat/webapps/
COPY orchestrationapp.war /opt/tomcat/webapps/
COPY reservationprovideservice.war /opt/tomcat/webapps/
COPY Gxpprovideservice.war /opt/tomcat/webapps/
COPY atsprovideservice.war /opt/tomcat/webapps/

#COPY listenerapp-config.properties /opt/tomcat/lib/

#Step1:sudo docker build -t provideflow:2 /tmp/docker_demo2/provideflow_docker
#Step2:sudo docker run -d -p 8080:8080 provideflow:2 or  docker run -it --rm -p 8080:8080 provideflow:2
#Step3:sudo docker exec -it <containerid> /bin/bash
