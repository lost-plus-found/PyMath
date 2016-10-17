output:
```
~ $ echo "1+2" | bc
3
~ $ echo "1+2" | pymath
3
~ $ echo "7/3.0" | bc
2
~ $ echo "7/3.0" | pymath
2.33333333333
~ $ echo "scale=4; 7/3.0" | bc
2.3333
~ $ echo "6**2" | bc
(standard_in) 1: syntax error
~ $ echo "6**2" | pymath
36
~ $ echo "math.factorial(15)" | pymath
1307674368000
~ $ echo "math.log(10)" | pymath
2.30258509299
~ $ echo "l(10)" | bc -l
2.30258509299404568401
~ $ echo "6^2" | bc
36
~ $ echo "4&5" | bc
(standard_in) 1: syntax error
~ $ echo "4&5" | pymath 
4
~ $ echo " hex(int('12340', 16) + int('5678', 16))  " | pymath
0x179b8

```
