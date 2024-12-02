# mvn-artifact
Personal maven artifact repository

## Add to your project as a dependency
### Maven
```xml
<dependency>
  <groupId>YOUR.PROJECT.GROUPID</groupId>
  <artifactId>ARTIFACT-ID</artifactId>
  <version>VERSION</version>
</dependency>
```

### Maven add the mvn-artifact repository
```xml
<repository>
  <id>ARTIFACT-ID</id>
  <url>https://raw.github.com/REPOSITORYOWNER/REPOSITORY-NAME/</url>
</repository>
```
