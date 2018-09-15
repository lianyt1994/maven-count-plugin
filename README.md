# maven-count-plugin
用来计算项目行数的maven插件

mvn clean install安装到本地仓库

导入依赖
<build><br>
        <plugins><br>
            <plugin><br>
                <groupId>com.pubinfo</groupId><br>
                <artifactId>maven-count-plugin</artifactId><br>
                <version>1.0-SNAPSHOT</version><br>
                <executions><br>
                    <execution><br>
                        <id>count line number</id><br>
                        <phase>install</phase><br>
                        <goals><br>
                            <goal>count</goal><br>
                        </goals><br>
                    </execution><br>
                </executions><br>
            </plugin><br>
        </plugins><br>
</build><br>

mvn com.pubinfo:maven-count-plugin:1.0-SNAPSHOT:count 执行
