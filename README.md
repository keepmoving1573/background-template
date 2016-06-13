# background-template

### 前言 ###

这是一个后台管理项目的通用模板。

### 软件环境 ###
IntelliJ IDEA 15.0

jdk 1.8

maven 3.3.9

### 使用的技术 ###
使用spring-boot + mybatis + freemarker

后期会陆续加入其他技术，将会更新到此文档

### 使用建议 ###

background-template作为一个种子项目，你可以基于它，快速搭建项目原型，并基于自己的业务场景修改源码。


### 更新日志 ###

#### 1.0 ####

1. 搭建基础环境，完成CRUD基础搭建，并在controller类，写出一个简单的查询。

------

### 怎么使用本项目 ###

1. git clone git@github.com:heikehuan/background-template.git
2. 在MySQL中导入 background-template/src/main/resources/test.sql 脚本
3. 更新 background-template/src/main/resources/application.yml 中username和password的值
4. cd background-template
5. mvn war:war
6. 使用命令java -jar background-template-1.0-SNAPSHOT.war直接启动war包

### 在IDE 中查看源码并运行 ###

**1. 在IntelliJ IDEA (推荐使用)**

File -> Import Project -> select background-template folder -> create project form existing sources -> ...

**2. 在Eclipse**

File -> Import -> Existing Maven Projects -> ...
