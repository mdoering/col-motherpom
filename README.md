# motherpom
Base Maven pom shared by all Catalogue of Life Maven projects. Captures the common settings, plugins and profiles that
are shared by majority of CoL projects. This pom artifact contains plugins to facilitate tasks like: deploy artifacts in a Maven repository, 
run integration tests, execute unit tests and package jar files.


## How to use this artifact
In a Maven pom.xml file use it as the parent pom using the current version of this artifact:

```
<parent>
  <groupId>org.col</groupId>
  <artifactId>motherpom</artifactId>
  <version>XX</version>
</parent>
```
