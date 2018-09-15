# maven-count-plugin
用来计算项目行数的maven插件

mvn clean install安装到本地仓库

导入依赖
<build></br>
        <plugins>
            <plugin>
                <groupId>com.pubinfo</groupId>
                <artifactId>maven-count-plugin</artifactId>
                <version>1.0-SNAPSHOT</version>
                <executions>
                    <execution>
                        <id>count line number</id>
                        <phase>install</phase>
                        <goals>
                            <goal>count</goal>
                        </goals>
                    </execution>
                </executions>
            </plugin>
        </plugins>
</build>

mvn com.pubinfo:maven-count-plugin:1.0-SNAPSHOT:count 执行
