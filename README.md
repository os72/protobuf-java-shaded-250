protobuf-java-shaded-250
========================

Protocol Buffer Java API - shaded version 2.5.0

---

Provides protobuf-java 2.5.0 in a separate namespace `com.github.os72.protobuf250` to help resolve runtime compatibility issues when other protobuf-java versions are needed in the same application

See also
* https://github.com/os72/protoc-jar
* https://github.com/os72/protoc-jar-maven-plugin
* https://github.com/google/protobuf

#### Usage

* Use package dependency `protobuf-java-shaded-250` instead of `protobuf-java`
* Use Java namespace `com.github.os72.protobuf250` instead of `com.google.protobuf`

Note that the namespace replacement must be applied to code generated by the protoc compiler as well. `protoc-jar` and `protoc-jar-maven-plugin` will support this feature out of the box

#### Maven dependency
```xml
<dependency>
  <groupId>com.github.os72</groupId>
  <artifactId>protobuf-java-shaded-250</artifactId>
  <version>0.9-SNAPSHOT</version>
</dependency>
```
