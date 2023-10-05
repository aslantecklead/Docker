FROM openjdk:11

RUN mkdir /app

COPY game.java /app/

WORKDIR /app

RUN javac game.java

CMD ["java", "game"]
