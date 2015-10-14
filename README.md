# ssm-scaffold
这是一个SpringMVC+Mybatis 脚手架，方便平时的开发使用，也可作为新手的学习项目。

##依赖
 - Spring :4.2.1.RELEASE
 - mybatis:3.3.0
 - mybatis-spring:1.2.3
 - druid:1.0.15
 - fastjson:1.2.7
 - mybatis-generator:1.3.2
 - pagehelper:4.0.1
 - slf4j:1.7.12
 - log4j:1.2.17

数据库默认使用了mysql，依赖
 - mysql-connection-java:5.1.6

这些能在pom.xml的顶部快速找到，直接修改：

	<properties>
        <junit-version>3.8.1</junit-version>
        <spring-version>4.2.1.RELEASE</spring-version>
        <mybatis-version>3.3.0</mybatis-version>
        <mybatis-spring-version>1.2.3</mybatis-spring-version>
        <druid-version>1.0.15</druid-version>
        <fastjson-version>1.2.7</fastjson-version>
        <mysql-connection-version>5.1.6</mysql-connection-version>
        <mybatis-generator-version>1.3.2</mybatis-generator-version>
        <pagehelper-version>4.0.1</pagehelper-version>
        <slf4j-version>1.7.12</slf4j-version>
        <log4j-version>1.2.17</log4j-version>
    </properties>

## 配置说明
 - applicationContext.xml:Spring 配置文件
 - generator.properties:Mybatis-generator 配置文件
 - generatorConfig.xml:Mybatis-generator 配置文件
 - jdbc.properties:jdbc配置文件
 - log4j.properties:log4j 配置文件
 - mvc-dispatcher-servlet.xml:SpringMVC配置文件

##快速上手
http://1994.github.io/2015/10/14/ssm-scaffold/