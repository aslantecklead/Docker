FROM openjdk:11

RUN mkdir /app

COPY calc.java /app/

WORKDIR /app

RUN javac calc.java

CMD ["java", "calc"]