[![Community Extension](https://img.shields.io/badge/Community%20Extension-An%20open%20source%20community%20maintained%20project-FF4700)](https://github.com/camunda-community-hub/community)
![Compatible with: Camunda Platform 8](https://img.shields.io/badge/Compatible%20with-Camunda%20Platform%208-0072Ce)
[![](https://img.shields.io/badge/Lifecycle-Incubating-blue)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#incubating-)

# Simple Camunda Zeebe Spring Boot Project

Configure a non-standard CA certificate: 
```
export JAVA_TOOL_OPTIONS="-Djavax.net.ssl.trustStore=keystore.jks -Djavax.net.ssl.trustStorePassword=changeit"
```

Then run the project: 
```shell
mvn clean install
mvn spring-boot:run
```