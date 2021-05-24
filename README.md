# Math Donut with docker

This code is an aplication of the "Donut math" made by a1k0n in 2006 using docker-compose

## How to use
Spin up the docker container and attach 'gcc' to it
```console
docker-compose up -d
docker attach gcc
```

CD into the code directory and compile/run your program
```console
cd code
gcc donut.c -o donut
./donut
```

## Credits
 - [https://www.a1k0n.net/2021/01/13/optimizing-donut.html](https://www.a1k0n.net/2021/01/13/optimizing-donut.html) 