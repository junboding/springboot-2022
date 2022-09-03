# springboot-2022
springboot learning jurney

application.properties

spring.application.name=nacos-test

server.port=18080

#spring.profiles.active:dev

spring.cloud.nacos.discovery.server-addr=127.0.0.1:8848

spring.cloud.nacos.config.server-addr=127.0.0.1:8848

spring.cloud.nacos.config.file-extension=properties

management.endpoints.web.exposure.include=*

management.metrics.tags.application=nacos-test
