# maven-repo

我的个人maven仓库.

## Usage
pom.xml:
```xml
    <repositories>
        <repository>
            <id>yulongs-maven-repo</id>
            <url>https://raw.githubusercontent.com/yulongshen/maven-repo/master/repository</url>
        </repository>
    </repositories>
    
    <dependencies>
		  <dependency>
			   <groupId>com.yulongs</groupId>
			   <artifactId>mybatis-generator-plugin</artifactId>
			   <version>1.0.0</version>
		  </dependency>
    </dependencies>  
```
