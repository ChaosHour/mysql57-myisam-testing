## Ran the follwoing test

```bash
Worked:
MySQL 5.7
Test 2:
make start-primary1 && make start-primary2
make create-myisam-table
make create-symlink
make restart-mysql-primary2
```

# Clean up
```bash
make stop
```
