## How to add my libraries (Using Maven pom.xml)
1. Add repository
```
    <repositories>
        <repository>
            <id>eFastTask</id>
            <name>eFastTask Libraries by Larry</name>
            <url>https://github.com/larry-do/mvn-repo/raw/master/</url>
        </repository>
    </repositories>
```
2. Add dependencies
```
        <dependency>
            <groupId>com.efasttask</groupId>
            <artifactId>efast-common</artifactId>
            <version>1.0</version>
        </dependency>

        <dependency>
            <groupId>com.efasttask</groupId>
            <artifactId>google-api</artifactId>
            <version>1.0</version>
        </dependency>
```
