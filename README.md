# Rest Showcase Webapp

Rest Showcase is a simple example of REST app build with the REST plugin.

Demo application: https://orders-demo.herokuapp.com/

## Deployment

### Local

Build application war using below maven command
```
mvn clean package
```

Start server using below command.

```
java -jar target/dependency/webapp-runner.jar target/*.war
```

Application will start on http://localhost:8080

### Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
