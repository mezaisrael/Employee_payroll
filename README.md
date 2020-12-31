# Employee payroll
Rest api built with Sprin Boot framework to mange employees pay roll.

### list all employees
```
$ curl -v localhost:8080/employees
```

### create a new emplyee
```
$ curl -X POST localhost:8080/employees -H 'Content-Type:application/json' -d '{"name": "Israel Meza", "role": "software engineer"}'
```

### update an employee
```
$ curl -X PUT localhost:8080/employees/3 -H 'Content-type:application/json' -d '{"name": "Israel", "role": "Senior software engineeri}'
```
