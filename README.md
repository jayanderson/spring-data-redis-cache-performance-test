Performance test for RedisCache from spring-data-redis. Multiple threads
repeatedly try to 'get' from the cache to the point that they block waiting for
a connection from the redis connection pool.
