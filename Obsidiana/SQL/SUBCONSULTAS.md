-- --

_EJEMPLO_

```SQL
SELECT id, salary
FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```