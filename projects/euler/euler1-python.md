    list = []
    for n in range(1,1000):
      if n % 3 == 0 or n % 5 == 0:
        list.append(n)
    print(sum(list))
