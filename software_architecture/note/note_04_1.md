#note

4+1 architecture view model

UML diagram
    Behavior
        Use Case
        Activity
        Sequence
    Structure
        Class

Use Case
![img.png](img.png)
Association
include
    check out - include -> add to cart
extend
    increase number product in cart - extend -> check out (nice to have)
Generalization
---
use case
    verb
redundant use case
    log in/log out

https://github.com/200lab-Education/sa-design-system-course/blob/master/problem/web_looker_tiny_url.md

---
Lucy Book Store

entity
    book
    customer
        uuid
        name
        phone
    book metadata

actor
    customer
uc
    rent book 
    view book catalog 
