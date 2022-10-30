FROM openjdk:11

ADD app.jar /root/
RUN echo "Asia/shanghai" > /etc/timezone
RUN chmod a+x  /root/app.jar

RUN mkdir /root/logs

ENTRYPOINT ["java","-jar","/root/app.jar"]

