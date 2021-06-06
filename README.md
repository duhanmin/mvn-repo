# mvn-repo

## Maven引入Jar包

下载源
```xml
<repositories>
    <repository>
        <id>maven-repo-master</id>
        <url>https://raw.github.com/duhanmin/mvn-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

日志工具包
```xml
<dependency>
    <groupId>com.duhanmin</groupId>
    <artifactId>log-router</artifactId>
    <version>0.1.1</version>
</dependency>
```
