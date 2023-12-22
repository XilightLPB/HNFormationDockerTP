FROM java:openjdk-8u111-jdk-alpine


COPY . /usr/src/myjavatests


WORKDIR /usr/src/myjavatests/src


RUN javac Main.java
RUN javac SetOfTests.java

CMD java Main && java SetOfTests

