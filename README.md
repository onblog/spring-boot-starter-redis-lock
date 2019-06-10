# spring-boot-starter-redis-lock

SnowJean项目的衍生品，使用非常简单。

## Maven

```xml
<dependency>
  <groupId>cn.yueshutong</groupId>
  <artifactId>spring-boot-starter-redis-lock</artifactId>
  <version>0.0.1.RELEASE</version>
</dependency>
```

## Use

```java

    @Autowired
    private RedisLock lock;

    //加锁
    lock.lock(key, value);
    
    //解锁
    lock.unlock(key, value);

```