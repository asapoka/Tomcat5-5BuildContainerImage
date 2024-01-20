FROM openjdk:8-jdk
WORKDIR /usr/local
RUN wget https://archive.apache.org/dist/tomcat/tomcat-5/v5.5.36/bin/apache-tomcat-5.5.36.tar.gz && \
    wget https://archive.apache.org/dist/tomcat/tomcat-5/v5.5.36/bin/apache-tomcat-5.5.36-admin.tar.gz && \
    tar xvf apache-tomcat-5.5.36.tar.gz && \
    tar xvf apache-tomcat-5.5.36-admin.tar.gz && \
    rm -f apache-tomcat-5.5.36.tar.gz && \
    rm -f apache-tomcat-5.5.36-admin.tar.gz
ENV JAVA_HOME=/usr/local/openjdk-8
ENV TOMCAT_HOME=/usr/local/apache-tomcat-5.5.36
ENV CATALINA_HOME=/usr/local/apache-tomcat-5.5.36
ENV PATH=$PATH:$JAVA_HOME/bin:$CATALINA_HOME/bin
ENV CLASSPATH=.:$JAVA_HOME/jre/lib:$JAVA_HOME/lib:$JAVA_HOME/lib/tools.jar:$CATALINA_HOME/common/lib