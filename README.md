# Java Socket Example

Hey I just want to test pull request!

redis是高性能的key-value数据库
运行在内存上-速度快

数据类型
1:string	set/get
2:List 		lpush/rpop(进栈出栈，)
3:Hash(适合存储对象 2的23次方-1) hget/hset
4:set(集合成员唯一)	sadd/smembers
5:sorted Set(有序集合)	zadd/zrange

ttl命令以秒为单位返回key的剩余过期时间
expire 设置过期时间

pub/sub	发布订阅
