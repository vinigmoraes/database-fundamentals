# Atomicity

It's mean that a database transaction must be executed successfully

For example, if we have two queries inside a transaction, all queries must be executed successfully without any error.

Example:

```
UPDATE person p
SET p.name = 'João'
where p.id = 1

UPDATE person p
SET p.name = 'Lucas'
where p.id = 3
```
