# Spring Boot HelloWorld (Java 8)

一个最简洁的 **Spring Boot HelloWorld 模版**，兼容 **Java 8 (JDK1.8)**。  
可以直接用作新项目的脚手架，也可以作为学习 Spring Boot 的入门示例。

---

## 🚀 快速开始

### 环境要求
- **JDK 1.8**
- **Maven 3.6+**（项目已内置 `mvnw`，无需额外安装 Maven）
- **Git**

### 克隆项目

```bash
git clone https://github.com/yourname/springboot-helloworld-jdk8.git myproject
cd myproject
```

### 启动应用

使用内置的 mvnw 启动:

```
./mvnw spring-boot:run
```
或者打包成 jar 再运行：
```
./mvnw clean package
java -jar target/helloworld-0.0.1-SNAPSHOT.jar
```

### 访问接口

应用启动后，打开浏览器访问：

👉 http://localhost:8080/

输出：

Hello, Spring Boot (Java 8)!

## 使用方法（作为模版）

在 GitHub 上点击 Use this template，即可基于该模版创建新仓库。

或者手动克隆后修改：
```
git clone https://github.com/yourname/springboot-helloworld-jdk8.git myapp
cd myapp
rm -rf .git   # 清理旧仓库信息
git init
git remote add origin git@github.com:yourname/myapp.git
git push -u origin main
```

