# docker build --tag tomcat8_new:1.0 .
FROM tomcat:8.5.54-jdk8-openjdk
 
#ENV JAVA_OPTS "-Djava.awt.headless=true -server -Xms2144m -Xmx2144m -XX:NewSize=256m -XX:MaxNewSize=256m -XX:PermSize=256m -XX:MaxPermSize=256m -XX:+DisableExplicitGC"

COPY context.xml /usr/local/tomcat/conf/
COPY server.xml /usr/local/tomcat/conf/
# Binary
#COPY rest-service-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war
