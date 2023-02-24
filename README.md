# Meshed Cloud Client 
## Maven Archetype

## 推送制品库
```shell
mvn clean install org.apache.maven.plugins:maven-deploy-plugin:2.8:deploy -DskipTests
```


## 使用方法
```shell
mvn archetype:generate -DarchetypeGroupId=cn.meshed.archetype -DarchetypeArtifactId=meshed-cloud-client-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=cn.meshed.cloud.rd  -DartifactId=meshed-cloud-rd  -Dversion=1.0.0-SNAPSHOT  -Dpackage=cn.meshed.cloud.rd -Ddomain=project
```
