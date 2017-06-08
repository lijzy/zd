FROM 10.9.152.126:5000/ht-standard/ht:base

COPY HT1610-0.0.1-SNAPSHOT.war $CATALINA_HOME/webapps/ROOT/ROOT.war
WORKDIR $CATALINA_HOME/webapps/ROOT
RUN jar xvf ROOT.war && rm -rf ROOT.war

expose 8080

CMD ["/usr/local/src/apache-tomcat-7.0.55/bin/catalina.sh", "run"]
