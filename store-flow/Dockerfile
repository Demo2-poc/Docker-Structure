# Pull base image
From rossbachp/apache-tomcat8

# Maintainer
MAINTAINER "Disney <demo2poc@disney.com">

# Copy to images tomcat path
COPY ticketingapp.war /opt/tomcat/webapps/
COPY ticketing-payload-service.war /opt/tomcat/webapps/
COPY store-service.war /opt/tomcat/webapps/
COPY gxpapp.war /opt/tomcat/webapps/
COPY gxp-service.war /opt/tomcat/webapps/
COPY guest-service.war /opt/tomcat/webapps/
COPY ev-service.war /opt/tomcat/webapps/
COPY dreamsapp.war /opt/tomcat/webapps/

COPY ticketingapp-config.properties /opt/tomcat/lib/
COPY ticketing-payload-service-config.properties /opt/tomcat/lib/
COPY storeservice-config.properties /opt/tomcat/lib/
COPY gxpapp-config.properties /opt/tomcat/lib/
COPY gxpservice-config.properties /opt/tomcat/lib/
COPY guestservice-config.properties /opt/tomcat/lib/
COPY evservice-config.properties /opt/tomcat/lib/
COPY dreamsapp-config.properties /opt/tomcat/lib/
COPY log4j.properties /opt/tomcat/lib/

#Step1:sudo docker build -t storeflow:2 /tmp/docker_demo2/storeflow_docker
#Step2:sudo docker run -d -p 8080:8080 storeflow:2 or  docker run -it --rm -p 8080:8080 storeflow:2
#Step3:sudo docker exec -it <containerid> /bin/bash
