### 1. before the package. 

```
export BRAINTREE_MERCHANT_ID=<BRAINTREE_MERCHANT_ID=>
export BRAINTREE_PUBLIC_KEY=<BRAINTREE_PUBLIC_KEY>
export BRAINTREE_PRIVATE_KEY=<BRAINTREE_PRIVATE_KEY>
export RECAPTCHA_PUBLIC_KEY=<RECAPTCHA_PUBLIC_KEY>
export RECAPTCHA_PRIVATE_KEY=<RECAPTCHA_PRIVATE_KEY>
```

### 2. make
``
mvn package clean
``

### Running The Server
```
java -jar webapp/target/dependency/webapp-runner.jar --port 8081 --path pizzeria webapp/target/*.war
```

#### Verify

Go to [http://localhost:8081/pizzeria/](http://localhost:8081/pizzeria/) to check that the app is up and running.

### Requirements
```java-8-openjdk```

## Built With
