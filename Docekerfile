FROM tomcat:8.0
MAINTAINER Bhanu
# COPY path-to-your-application-war path-to-webapps-in-docker-tomcat
COPY */target/hello-world-war-2.0.0.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD [“catalina.sh”, “run”]
