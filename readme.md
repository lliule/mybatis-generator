``````` 逆向生成mysql库表成实体
1、在pom.xml中指定 configurationFile 的值为 ${basedir}/src/main/resources/generatorConfig-mysql.xml
2、配置maven命令 ：mybatis-generator:generate -e 
3、点击运行


`````` 逆向生成oracle库表成实体
1、在pom.xml中指定 configurationFile 的值为 ${basedir}/src/main/resources/generatorConfig.xml
2、其他参考上面  mysql步骤