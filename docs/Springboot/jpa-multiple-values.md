---
layout: default
title: JPA - Getting multiple values from columns
parent: Spring Boot
permalink: /docs/springboot/jpa-multiple-values
---

# [JPA] Getting multiple values from columns

![picture 1](../../assets/docs/Springboot/JPA-multiple-values/1675611788006.png)

```java
List<Object[]> = {{10, 20}}
```
`List<Object[]>` receives nested array from the `@Query` method as above.


## Client
![picture 2](../../assets/docs/Springboot/JPA-multiple-values/1675612928245.png)  

`console.log(fetch_data[0])` prints `[10, 20]`.