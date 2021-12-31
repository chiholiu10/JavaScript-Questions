# JavaScript-Questions

# What is a Promise?
A promise is an object that shows the completion of an asynchronous operation and value. Furthermor there are 3 different states of promise objects:
  - Pending: Initial State, before the Promise succeeds or fails.
  - Resolved: Completed Promise
  - Rejected: Failed Promise, throw an error

(mnemonic: PRR) 

# What are the differences between synchronous  and async
  - Synchronous will perform each task one at time. So you need to wait till it finishes a task before moving to another. 
  - Asynchronous means it will move to another task before the prevous one finishes. So in fact you are dealing with multiple request simultaneously, which             theoretically resulted in shorter loading time. 

# When to use synchronous or asynchronous.
  - In fact it really depends on different aspects. For instance a profile and product must be loaded first in order to see the orders. In that case it is possible to use asynchronous, but keep in mind that product and profile should not load after the orders. 

# What are the main differences between callback, promise and async

Anyone feel free to improve or add JavaScript questions/answers. 
