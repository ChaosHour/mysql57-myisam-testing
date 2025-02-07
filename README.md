## Ran the follwoing test

What is needed to run this test:
- MySQL Client
- Create two folders in the root of this project called shared_data and shared_data2
- Docker


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
