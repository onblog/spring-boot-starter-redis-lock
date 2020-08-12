# spring-boot-starter-redis-lock

SnowJean项目的衍生品，使用非常简单，前提是你的spring boot已经集成并开启redis。

## Use

``` java

    @Autowired
    private RedisLock lock;

    //加锁
    lock.lock(key, value);
    
    //解锁
    lock.unlock(key, value);

```
