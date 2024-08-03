# sum of all even numbers and odd numbers
lst=[1,2,3,4,5,6,7,8,9,10,12,13,14,15]

even_sum=0
odd_sum=0
for i in lst:
    if i%2==0:
        even_sum=even_sum+i
    else:
        odd_sum=odd_sum+i
print(even_sum,odd_sum)
        
