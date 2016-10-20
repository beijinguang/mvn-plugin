maven插件开发helloworld
---
- helloworld 插件
- test-plugin 插件测试

### 引用插件
```
<build>
    <plugins>
        <plugin>
            <groupId>com.idea4j</groupId>
            <artifactId>maven-plugin-helloworld</artifactId>
            <version>1.0-SNAPSHOT</version>
            <executions>
                <execution>
                    <phase>process-resources</phase>
                    <goals>
                        <goal>testgo</goal>
                    </goals>
                </execution>
            </executions>
        </plugin>
    </plugins>
</build>
```
