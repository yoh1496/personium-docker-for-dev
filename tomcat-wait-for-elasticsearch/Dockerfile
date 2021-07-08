FROM tomcat:9-jdk8-adoptopenjdk-hotspot

WORKDIR /usr/local/tomcat/bin
COPY entrypoint.sh ./

EXPOSE 8080

ENTRYPOINT [ "entrypoint.sh" ]
