FROM 10.9.152.126:5000/ht-standard/ht:base

COPY HT1610-0.0.1-SNAPSHOT.war $CATALINA_HOME/webapps/ROOT/ROOT.war
RUN jar xvf $CATALINA_HOME/webapps/ROOT/ROOT.war && rm -rf $CATALINA_HOME/webapps/ROOT/ROOT.war
