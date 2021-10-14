# hello-world
first repository trial in GitHub
#i'm going to add random codes here as an edit or update
'''
trial = open('trial_1.txt')
r_file = trial.read()
print(r_file)
print('enter number:')
typed = input()
print(typed)
if int(typed) == int(r_file):
    print('file opened')
else:
    print('text does not match')

i=1
while i <5:
    print('Devaki' , i)
    i+= 1
    n= i%3
    if n==0:
        print(i, 'fish', n,  'sheep')
        
    elif i> 3:
        continue
    else:
        break

for i in range (0,15, 2):
    print(i)

days = ['Mon', 'Tues', 'Wed', 'Thurs', 'Fri', 'Sat', 'Sun']
j =4
for i in days:
    print ('date is ', j, 'Oct, and the day is ', i)
    j+=1
import random

for i in range (9):
    print(random.randint(1,10))


def what(i):
    print('what did you say,' +i+ '?')
    print('i did not hear you, ' +i)
    print(i+ 'i beg your pardon?')

what('bob')



def simpleInterest(amount,rate,year):
    return amount*rate*year/100

print ('Amount', 'Interest', sep='\t', end='\n\n')
for i in range (5):
    n= simpleInterest((i*500),3,2)
    print ( i*500, n, sep='\t' )


music = [0,1,2,3,4,5]
print(music, end='\n\n')

music[2] = music[0]
print(music)

lol= music*2
music = music + lol
print(music)
del music[5]
print(music)

for index, item in enumerate(music):
	print(str(index), item, sep='\t')



tup_1 = (0,1,2,3,4,5)

print(tup_1[2])

#tup_1[2] = 3
#del(tup_1[2])

'''










    
    
