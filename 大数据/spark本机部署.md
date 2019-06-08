spark本机部署

版本 2.4.3

1、修改 spark-env.sh

export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_40.jdk/Contents/Home
export HADOOP_CONF_DIR=/usr/local/Cellar/hadoop/3.1.1/libexec/etc/hadoop
export SPARK_MASTER_HOST=localhost
export SPARK_MASTER_PORT=7077

2、配置 slaves

localhost

3、启动

sbin/start-all.sh

4、web 访问
http://localhost:8080/
