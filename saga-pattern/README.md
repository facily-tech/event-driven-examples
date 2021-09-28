The idea is to implement a practical example of [saga pattern](https://microservices.io/patterns/data/saga.html)

## Problem

We have three(3) systems (order, stock and bank). Every order creation requires that the user has credit (the service bank controls it), and the product has stock (the service stock controls it)