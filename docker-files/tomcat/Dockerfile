FROM tomcat:8-jre11
LABEL "Project"="containerisation_of_webstack"
LABEL "Author"="Isak"
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
VOLUME /usr/local/tomcat/webapps