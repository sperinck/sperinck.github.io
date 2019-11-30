    primes = [2,3,5,7,11]; factors = []; target = 600851475143; root = int(target**0.5// 1)
    for n in range(12,1000): # compile relevant list of primes
      for p in primes:
        if p > n**0.5 // 1:
          trunc = primes[0:primes.index(p)]; break
      if all(n / p != n // p for p in trunc): primes.append(n)
    for p in primes:
      if target / p == target // p: factors.append(p)
    print(*factors)
