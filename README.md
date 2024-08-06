# ctf01d-service-example1-php

Example Service For ctf01d scoreboard system

## Run service

```
$ cd service
$ docker-compose up
```

## Run checker

**put flag**
```
cd checker
python3 -u checker.py 127.0.0.1 put abcdifghr c01d4567-e89b-12d3-a456-426655440000
```

**check flag**
```
cd checker
python3 -u checker.py 127.0.0.1 check abcdifghr c01d4567-e89b-12d3-a456-426655440000
```

## Run exploit

```
cd checker
python3 -u attack.py
```
