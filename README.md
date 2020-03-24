# First Maven Project

A sample project created by following tutorial: [Apach Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)

create:
```
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

build:
```
mvn package
```

run:
```
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
```