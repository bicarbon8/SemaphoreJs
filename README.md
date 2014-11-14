SemaphoreJs
===========

Javascript utility for providing a semaphore locking mechanism

[JSDoc Documentation](http://rawgit.com/bicarbon8/SemaphoreJs/master/out/SemaphoreJs.html)

## Usage:

```
SemaphoreJs.lock(uniqueName, successCallback[[, timeoutCallback], maxWaitTime]);
```
or
```
SemaphoreJs.lockFor(uniqueName, successCallback, duration);
```