# Overview

## Install Maven Archetype

`mvn clean install`

## Using Maven Archetype

```
mvn archetype:generate \
-DarchetypeGroupId=com.example \
-DarchetypeArtifactId=poc-maven-archetype \
-DgroupId=com.example \
-DartifactId=poc-maven-archetype-app \
-Dversion=1.0-SNAPSHOT \
-Dpackage=com.example
```

# References

[Maven Archetype](https://www.baeldung.com/maven-archetype)

[Introduction to Archetypes](http://maven.apache.org/guides/introduction/introduction-to-archetypes.html)

[Guide Creating Archetypes](http://maven.apache.org/guides/mini/guide-creating-archetypes.html)