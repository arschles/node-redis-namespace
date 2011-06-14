# node-redis-namespace
Pretty much a clone of [redis-namespace](https://github.com/defunkt/redis-namespace) for node.

This is super-alpha, and still super buggy. Better docs and tests to come.

# Usage
You can use this library almost identically as you use [node_redis](https://github.com/mranney/node_redis)

    var redis-namespace = require('redis-namespace'),
        client = redis-namespace.createClient();
    //carry on as normal