# Average-of-numbers
n=int(input("how many elements:"))
list1=[]
for i in range(n):
    list1.append(int(input()))
sum_of_elements=sum(list1)
len_of_list1=len(list1)
average=sum_of_elements/len_of_list1
print(average)
