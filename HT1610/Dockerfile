FROM 10.9.91.208:5000/ht:0.0.1

COPY HT1610-0.0.1-SNAPSHOT.war $CATALINA_HOME/webapps/ROOT/ROOT.war
WORKDIR $CATALINA_HOME/webapps/ROOT
RUN jar xvf ROOT.war && rm -rf ROOT.war

expose 8080

CMD ["/usr/local/src/apache-tomcat-7.0.55/bin/catalina.sh", "run"]
