## 简单介绍
**启动和访问**

```bash
mvn clean package

java -jar target/actuator-demo-0.0.1-SNAPSHOT.jar

http://localhost:8080/hello
```


## Actuator
```bash
所有actuator endpoints都在 http://localhost:8080/actuator

例如:
Health: http://localhost:8080/actuator/health
Metrics: http://localhost:8080/actuator/metrics
Thread Dump: http://localhost:8080/actuator/threaddump
Environment: http://localhost:8080/actuator/env
```
