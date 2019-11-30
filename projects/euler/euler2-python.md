    list = [1,2]
    even = []
    while list[-1] +list[-2] <= 4000000:
      list.append(list[-1]+list[-2])
    for num in list:
      if num % 2 == 0: even.append(num)
    print(sum(even))
