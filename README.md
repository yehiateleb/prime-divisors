# prime-divisors
get you the prime divisors
def primedivisors(x) :
...     c =[]
...     for a in range(1,x+1):
...         if x%a == 0 :
...             b = isprime(a)
...             if b== "prime" :
...                 c.append(a)
...     return c
