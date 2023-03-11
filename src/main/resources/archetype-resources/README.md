# Meshed Cloud Client

> ${rootArtifactId}

## 推送制品库
```shell
mvn clean install org.apache.maven.plugins:maven-deploy-plugin:2.8:deploy -DskipTests
```

## 使用Client
Maven
```xml
<dependency>
    <groupId>${groupId}</groupId>
    <artifactId>${rootArtifactId}</artifactId>
    <version>${version}</version>
</dependency>
```