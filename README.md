

# service run 
xxxx is variable. input to fit your environment. 
```
docker run -it -d --name sonarqube 
-p 9000:9000 
-e SONARQUBE_JDBC_USERNAME=xxxxxx 
-e SONARQUBE_JDBC_PASSWORD=xxxxxxx 
-e SONARQUBE_JDBC_URL="jdbc:mysql://xxx.xxx.xxx.xxx:3306/xxxxxx?useUnicode=true&characterEncoding=utf8&rewriteBatchedStatements=true" 
sonarqube:lts

```

# in case of our campnay - groobee sonarqube in cow server.
```
docker run -it -d --name sonarqube 
-p 9000:9000 
-e SONARQUBE_JDBC_USERNAME=groobeesonar
-e SONARQUBE_JDBC_PASSWORD=xxxxxxx 
-e SONARQUBE_JDBC_URL="jdbc:mysql://xxx.xxx.xxx.93:3306/groobee_sonar?useUnicode=true&characterEncoding=utf8&rewriteBatchedStatements=true" 
sonarqube:lts
```
