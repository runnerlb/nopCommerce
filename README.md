# nopCommerce #

学习nopCommerce源码，加入自己的注释和见解

## Librarise ##

* Nop.Core
  * Caching
    * ICacheManager 提供了缓存的接口
    * MemoryCacheManager 实现了ICacheManager接口，在内存中进行缓存数据
    * RedisCacheManager 实现了ICacheManager接口，在Redis中进行缓存数据
    * PerRequestCacheManager 实现了ICacheManager接口，通过Http进行缓存
    * NopNullCache 实现了ICacheManager接口，Nop自己的缓存
    * IRedisConnectionWrapper Redis连接的封装接口
    * RedisConnectionWrapper 实现Redis连接接口
    * Extensions 缓存接口的扩展方法
  * ComponentModel
  * Configuration
  * Data
  * Domain
  * Events
* Nop.Data

* Nop.Services

## Plugins ##

## Presentation ##

## Tests ##
