
Backend init
```
./init.sh
```
Delete all data in database
```
docker compose run --rm django cleardatabase
```
Create admin user
```
docker compose run --rm django createsuperuseradmin
```
Create default data
```
docker compose run --rm django createdefaultdata
```
Run tests
```
docker compose run --rm django test
```
