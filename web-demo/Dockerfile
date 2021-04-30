FROM 192.168.22.11/kubernetes/tomcat:8.0.51-alpine

COPY target/web-demo-1.0-SNAPSHOT /usr/local/tomcat/webapps/ROOT

COPY dockerfiles/start.sh /usr/local/tomcat/bin/start.sh

ENTRYPOINT ["sh" , "/usr/local/tomcat/bin/start.sh"]
