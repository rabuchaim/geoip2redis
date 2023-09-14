# GeoIP2Fast for Redis

GeoIP2FastRedis is the fastest GeoIP2 country lookup library. Automatically import all data to your server with your own updated data file with Maxmind-Geolite2-CSV and it's Pure Python and Pure Redis Protocol!


## GeoIP2FastRedis v0.0.1 - Preview

### - All data uses 60Mb of Redis server (94 keys)
### - Imports 440K networks in less than 3 seconds
### - Load the main index into memory in 0.15 seconds.
### - Use less than 1Mb of footprint
### - A search takes around 0.00007 seconds
### - If the search is cached, it takes less than 0.000001 seconds
### - Performs >15K searches per second, per core (without cache)


![](https://raw.githubusercontent.com/rabuchaim/geoip2redis/main/images/redis_import.jpg)


![](https://raw.githubusercontent.com/rabuchaim/geoip2redis/main/images/geoip2redis_test.jpg)


![](https://raw.githubusercontent.com/rabuchaim/geoip2redis/main/images/geoip2redis_speedtest.jpg)