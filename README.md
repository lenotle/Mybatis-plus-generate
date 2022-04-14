## 项目介绍

Mybatis-plus代码生成器，使用过 AutoGenerator 可以快速生成 Mapper接口、 Entity实体类 及Mapper XML文件、 Service 、Controller 等各个模块的代码。

### 依赖

```java
<dependency>
    <groupId>com.baomidou</groupId>
    <artifactId>mybatis‐plus‐generator</artifactId>
    <version>3.1.0</version>
</dependency>

```

### 项目运行方式

在src\main\java\com\lepay\generator目录中运行MyBatisPlusGenerator.java程序

### tips

输入模块名： tip

注意：模块名匹配表名前缀会自动去掉，否则生成的模型类保留前缀。

### 自定义模板

自动生成代码是通过freemarker 引擎生成代码，可以通过自定义freemarker模板对生成代码进行个性化定义。 在resources下创建templates目录，目录下放入要个性化定义模板即可。

