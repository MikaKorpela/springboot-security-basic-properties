# springboot-security-basic-properties #

The ```spring-boot-starter-security``` dependency enables the authentication and authorization in all end-points.

The following properties override the default user creation; see `springboot-security-basic-default`.

```yaml
spring:
  security:
    user:
      name: donald
      password: duck
```

The properties based security configuration does not include any settings for authorization.
