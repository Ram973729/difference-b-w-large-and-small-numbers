# difference-b-w-large-and-small-numbers
n=int(input('Enter how many numbers you want:'))
num=int(input('Enter any number:'))
large=num
small=num
i=1
while(i<n):
    num=int(input('Enter any number:'))
    if(num>large):
        large=num
    if(num<small):
        small=num
    i=i+1
print('THe difference between them is',large-small) 
