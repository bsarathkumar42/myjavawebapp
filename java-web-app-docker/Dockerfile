FROM openjdk:8-alpine
# RUN sed -i '/<\/tomcat-users>/ i\<user username="sarath" password="sarath" roles="admin-gui,manager-gui"/>' /usr/local/tomcat/conf/tomcat-users.xml 
# RUN sed -i '19,20d' /usr/local/tomcat/webapps/manager/META-INF/context.xml
COPY target/java-web-app*.war /usr/local/tomcat/webapps/java-web-app.war

