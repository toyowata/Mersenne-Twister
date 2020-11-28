# Mersenne Twister - generate random number using TRNG on Mbed target

## How to build

```
$ git clone https://github.com/toyowata/Mersenne-Twister
$ cd Mersenne-Twister
$ mbed deploy
$ mbed compile -m auto -t gcc_arm
```

## Example output

```
10 outputs of genrand_real2() * 100 + 1
12.52412249
34.20398454
97.88892632
46.33632461
38.93198152
9.33679475
20.12405684
38.13969055
73.03554304
33.24510406
```
