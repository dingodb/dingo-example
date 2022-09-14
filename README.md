
# Examples Using Jar Release by Dingo

## 1.Maven Central Repository

### 1.1 Maven Central URL

#### 1.1.1 URL Address

- Snapshot

[Snapshot on Sonatype](https://s01.oss.sonatype.org/content/repositories/snapshots)

- Release

[Release on Sonatype](https://s01.oss.sonatype.org/content/repositories/releases)


#### 1.1.2 Repository for maven

```pom
    <repositories>
        <repository>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>never</updatePolicy>
                <checksumPolicy>fail</checksumPolicy>
            </snapshots>
            <name>Nexus Snapshots</name>
            <id>snapshots-repo</id>
            <url>https://s01.oss.sonatype.org/content/repositories/snapshots</url>
            <layout>default</layout>
        </repository>
    </repositories
```

- Notice

> For dingo-v0.4.0 version, now `dingo-xxx-0.4.0-SNAPSHOT` is available, the release version is not ready yet.


#### 1.1.3 Examples Using Maven Central

[DingoCliExample.java](./src/main/java/com/dingodb/DingoCliExample.java)


## 2.Github Repository