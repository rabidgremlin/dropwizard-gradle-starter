# Dropwizard Gradle Starter Project
Starter project for Dropwizard using Gradle as the build system. Code is from the [Dropwizard tutorial](http://www.dropwizard.io/1.0.0/docs/getting-started.html#tutorial)

Project uses ShadowJar to build an all-in-one, "fat jar".

## Getting going

1. Clone project

2. Run

```
gradle build
```

3. Start project

```
java -jar build/libs/dropwizard-gradle-starter-1.0.0-all.jar server src/main/yml/server.yml
```

4. Browse to:

* http://localhost:8080/hello-world
* http://localhost:8080/hello-world?name=Successful+Dropwizard+User
* http://localhost:8081/

5. See the [Next steps](http://www.dropwizard.io/1.0.0/docs/getting-started.html#next-steps) section of tutorial 