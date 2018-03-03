下载 apache-activemq-5.8.0 安装包
新建此项目，添加maven 依赖
<dependency>
    <groupId>org.apache.activemq</groupId>
    <artifactId>activemq-all</artifactId>
    <version>5.15.3</version>
</dependency>
将 apache-activemq-5.15.3\example 里面的类copy到项目中
进入 F:\study\activemq\apache-activemq-5.15.3\bin\win64
管理员身份启动 activemq.bat	
web控制台
http://localhost:8161/admin/
admin/admin
开放端口 amqp 5672，tcp 61616，stomp 61613，mqtt 1883
