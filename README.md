# share
#Игра кирпичный язык или что-то там...

VOWELS = list('qeyuioa')
x= list( input('standard word:'))
n = []

for i in x:
    if i not in VOWELS:
        n.append(i)
    else:
        n.extend(i +'s' + i)
print('brick lang:    ', *n , sep = '')
