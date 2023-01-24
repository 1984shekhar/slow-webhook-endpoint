#### We can set application configuration in file
```
src/main/resources/application.properties
```
#### We can configure timeout in milliseconds
```
timeOut = 10000
```
#### We can configure serviceuri for webhook endpoint with following configuration. This is default set to 9090 port.
```
serviceuri = localhost:9090
```

#### We can build and run application with following commands. 
```
mvn clean package
java -jar target/rest-1.0.jar
```
