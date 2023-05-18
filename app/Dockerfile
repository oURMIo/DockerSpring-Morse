FROM gradle

WORKDIR /app
COPY . .
RUN ./gradlew build --refresh-dependencies
RUN ./gradlew clean build
CMD ./gradlew bootRun
