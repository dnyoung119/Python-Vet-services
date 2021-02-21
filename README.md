# Python-Vet-services
Practice using python 3.x

print('Chanuceys Vet Services')
print()
print('Exam: 45')
print('Vaccinations: 32')
print('Trim Nails: 8')
print('Bath: 15')
cost = {'Exam': 45, 'Vaccinations': 32, 'Trim Nails': 8, 'Bath': 15, 'None': 0, 'none': 0}

first = input('Select first service: ')
second = input('Select second service: ')
total = cost[first] + cost[second]

if first=='Exam':
  print('Service 1 -',first+':',cost[first])
elif first=='Vaccinations':
  print('Service 1 -',first+':',cost[first])
elif first=='Trim Nails':
  print('Service 1 -',first+':',cost[first])
elif first=='Bath':
  print('Service 1 -',first+':',cost[first])
elif first=='None' or 'none':
  print('Service 1 -',first+':',cost[first])

if second=='Exam':
  print('Service 2 -',second+':',cost[second])
elif second=='Vaccinations':
  print('Service 2 -',second+':',cost[second])
elif second=='Trim Nails':
  print('Service 2 -',second+':',cost[second])
elif second=='Bath':
  print('Service 2 -',second+':',cost[second])
elif second=='None' or 'none':
  print('Service 2 -',second+':',cost[second])

print('Total:',total)
