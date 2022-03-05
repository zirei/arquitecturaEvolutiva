FROM openjdk:17.0.2-jdk-oracle
VOLUME /tmp
EXPOSE 9091
COPY bank-balance-0.0.1.jar /bank-balance-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-balance-0.0.1.jar" ]