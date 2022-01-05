# JavaScript-Questions

# What is a Promise?
A promise is an object that shows the completion of an asynchronous operation and value. Furthermor there are 3 different states of promise objects:
  - Pending: Initial State, before the Promise succeeds or fails.
  - Resolved: Completed Promise
  - Rejected: Failed Promise, throw an error

(mnemonic: PRR) 

# What are the differences between synchronous  and async
  - Synchronous will perform each task one at time. So you need to wait till it finishes a task before moving to another. 
  - Asynchronous means it will move to another task before the prevous one finishes. So in fact you are dealing with multiple requests simultaneously, which             theoretically resulted in shorter loading time. 

# When to use synchronous or asynchronous.
  - In fact it really depends on different aspects. For instance a profile and product must be loaded first in order to see the orders. In that case it is possible to use asynchronous, but keep in mind that product and profile should not load after the orders. 

# What are the main differences between callback, promise and async

# What is Function hoisting 

<img width="983" alt="Screenshot 2022-01-05 at 21 36 23" src="https://user-images.githubusercontent.com/16224390/148287501-24b3de14-7245-4ffb-975f-bd15746c845c.png">

When a callback is already called before declaring it. 

# What is var hoisting 

You always need to declare variable and assign value in order to return value, else it shows undefined. 
<img width="1051" alt="Screenshot 2022-01-05 at 21 43 10" src="https://user-images.githubusercontent.com/16224390/148287008-2c1d68d3-8f1f-4b3a-babe-dcbb8cbe804b.png">

if there is an initialization and no declaration 
<img width="1177" alt="Screenshot 2022-01-05 at 21 43 20" src="https://user-images.githubusercontent.com/16224390/148287041-d85af8ee-afa6-405a-8cde-56de12a37cdb.png">

# What is const/let hoisting 

<img width="1167" alt="Screenshot 2022-01-05 at 21 47 20" src="https://user-images.githubusercontent.com/16224390/148287091-84fad32e-a9de-4b04-aeec-0f4d521fc96b.png">

Anyone feel free to improve or add JavaScript questions/answers. 
