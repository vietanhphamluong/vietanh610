# vietanh610
# ex1
# inventory={
#     'gold':500,
#     'pouch': ['flint', 'twine','gemstone'],
#     'backpack':['xylophone','dagger','bedroll','bread loaf']
# }
# inventory['pocket'] = []
# inventory['pocket'] = [ 'seashell', 'strange berry', 'lint']
# inventory['backpack'].pop(1)
# inventory['gold']+= 50
# print(inventory)

# ex2
# prices={}
# prices['banana']=4
# prices['apples']=2
# prices['orange']=1.5
# prices['pear']=3
# stock={}
# stock['banana']=6
# stock['apples']=0
# stock['orange']=32
# stock['pear']=15
# total =[]
# for i in prices:
#     print(i)
#     print('price:',prices[i])
#     print('stock:',stock[i])
#     price =(prices[i]*stock[i])
#     print(price)
#     total.append(price)
# totalmoney = sum(total)
# print('the total money is:',totalmoney)

# ex3
# n ='Answer the following algebra question:If x = 8, then what is the value of 4(x+3)'
# print(n)
# print('1. 35','2. 36','3. 40','4. 44')
# wronganswers={'1':35,'2':36,'3':40}
# answer = input('your choice:')
# while True:
#     if answer in {'4':44}:
#         print('bingo')
#         break
#     if answer in wronganswers:
#         print(':(')
#         print(n)
#         print('1. 35','2. 36','3. 40','4. 44')
#         answer = input('choose again:')

# ex4
# n ='Answer the following algebra question:If x = 8, then what is the value of 4(x+3)'
# print(n)
# print('1. 35','2. 36','3. 40','4. 44')
# wronganswers={'1':35,'2':36,'3':40}
# answer = input('your choice:')
# countcorrect = []
# if answer in {'4':44}:
#         print('bingo')
#         countcorrect.append(1)
# if answer in wronganswers:
#         print(':(')
# print('Estimate this answer( exact calculation not needed):')
# print('Jack scored these marks in 5 math tests: 49, 81, 72, 66 and 52. What is the mean?')
# print('1. about 55')
# print('2. about 65')
# print('3. about 75')
# print('4. about 85')
# wronganswers2 = {'1':'55','3':'75','4':'85'}
# answer = input('your choice:')
# if answer in {'2':'65'}:
#         print('bingo')
#         countcorrect.append(1)
# if answer in wronganswers2:
#         print(':(')
# count = countcorrect.count(1)

# print('you corectly answer', count,'out of 2 questions')