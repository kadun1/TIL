### Basic Commands

- SET message 'Hi there!'
- GET message
  - message 는 변수나 key의 이름으로 사용했다.
- type 종류와 command
  - String : SET, GET, APPEND, STRLEN..
  - List : LPUSH, RPUSH, LPOP, RPOP, LINDEX, LLEN, LRANGE..
  - Hash : HSET, HGET, HGETALL, HDEL, HEXISTS, HKEYS, HVALS..
  - Set : SADD, SREM, SMEMBERS, SISMEMBER, SUNION, SINTER, SDIFF..
  - Sorted Set : ZADD, ZRANGE, ZRANK, ZSCORE, ZREM, ZINCRBY, ZRANGEBYSCORE..
  - Bitmap : GETBIT, BITCOUNT, BITOP..
  - HyperLogLog : PFADD, PFCOUNT, PFMERGE..
  - JSON : JSON.SET, JSON.GET, JSON.MGET, JSON.ARRAPPEND, JSON.OBJKEYS, JSON.OBJLEN..
  - Index : FT.CREATE, FT.ADD, FT.SEARCH, FT.AGGREGATE, FT.DROP..
- redis.io/commands 공식문서
