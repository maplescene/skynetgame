# skynet 的坑

* skynet.send(address, ...) 如果 address 对应的服务不存在, 不会报错

* skynet.call(address, ...) 如果服务不存在, 不会报错

* skynet.newservice(name, ...) 传进去的参数都会被转换成字符串

