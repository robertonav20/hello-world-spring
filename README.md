# hello-world-spring

Run with maven

```sh
    mvn spring-boot:run -Dspring-boot.run.jvmArguments="-Xdebug -Xrunjdwp:transport=dt_socket,server=y,suspend=n,address=5005"
```

Format files

```sh
    mvn spotless:apply
```

Format check

```sh
    mvn spotless:check
```
