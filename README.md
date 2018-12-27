# tomcatdockerfile


 docker run --name=sritom -d -v /opt/tomcat/apache-tomcat-8.5.14/webapps/:/usr/local/tomcat/webapps -p 8092:8080 tomcat

 docker cp context.xml 022685f43736:/usr/local/tomcat/webapps/manager/META-INF
 docker cp tomcat-users.xml 022685f43736:/usr/local/tomcat/conf
