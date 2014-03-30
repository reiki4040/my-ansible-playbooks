my-ansible-playbooks
====================

my playbooks for practice

ansible 1.5.3
MacOSX 10.9

## playbook list

* commons
* Supervisord
* nginx (package)
* responser(nginx from source + Lua + Redis)
* Growthforecast
* Elasticsearch (deb package)

## example Responser

example Nginx + Lua + Redis

refs
http://d.hatena.ne.jp/hiboma/20120205/1328448746

### set Redis cache

on app server
<pre>
redis-cli
redis 127.0.0.1:6379> set cache "show message when access to /lua-redis-cache"
</pre>
