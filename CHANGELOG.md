# Overpass Changelog

### 0.3.5 (2015-02-12)

* **[FIXED]** Fixed incorrect `icecave/isolator` version constraint

### 0.3.4 (2015-02-12)

* **[IMPROVED]** RPC server can now be shutdown gracefully by a signal handler

### 0.3.3 (2015-01-31)

* **[IMPROVED]** Improved logging and removed some noisy log messages

### 0.3.2 (2014-12-14)

* **[FIXED]** RPC exception messages are no longer propagated to the client unless the exception is an `ExecutionException`
* **[IMPROVED]** Improved consistency of logging

### 0.3.1 (2014-10-30)

* **[FIXED]** `AmqpRpcServer::exposeObject()` no longer exposes methods with names that begin with an underscore

### 0.3.0 (2014-10-29)

* **[BC]** Renamed `RpcClientInterface::call()` to `invokeArray()` and added `invoke($name, ...)`

### 0.2.0 (2014-10-29)

* **[NEW]** Added `RpcServerInterface::exposeObject()`

### 0.1.0 (2014-10-27)

* Initial release
