FROM tomcat:8.5.54-jdk8-openjdk
#FROM tomcat:9.0.34-jdk11-openjdk

LABEL maintainer="suporte@intersistemas.com.br"

COPY  grails3-0.1.war.original /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD ["catalina.sh", "run"]