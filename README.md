# Spring Boot config server

# To run the configuration server, simply use the command:
`.\gradlew bootRun`

You can navigate here to see the properties for the demo:

`http://localhost:8080/`

You can change the port by editing **application.properties** file

## Building docker image
You can build docker image by running following command inside the directory where `Dockerfile` is located.
- `docker build --build-arg JAR_FILE=build/libs/\*.jar -t account-fetching:0.0.1 .`
