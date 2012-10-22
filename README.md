# edn-mvn-repo

A *temporary* maven repository for publishing snapshots of [edn-java](http://github.com/bpsm/edn-java) [and](http://github.com/bpsm/edn-java-guava) [friends](http://github.com/bpsm/edn-java-joda).

## Usage

Add the following repository declaration to your pom.

```xml
<repositories>

  <repository>
    <id>my.mvn.repo</id>
    <url>https://github.com/bpsm/edn-mvn-repo/raw/master/snapshots<url>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
    </snapshots>
  </repository>

<repositories>
```

## Limitations

Really, the is a terrible idea. I'm working on getting things set up so that I can make use of [Sonatype's free open source maven repo hosting](https://docs.sonatype.org/display/Repository/Sonatype+OSS+Maven+Repository+Usage+Guide). 

