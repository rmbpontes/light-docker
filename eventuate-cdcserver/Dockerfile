FROM openjdk:8-jre-alpine
EXPOSE  8844
ADD /eventuate-cdc-server.jar server.jar
CMD ["/bin/sh","-c","java -Dlight-4j-config-dir=/config -Dlogback.configurationFile=/config/logback.xml -cp /server.jar com.networknt.server.Server"]
