# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 3

---

### AIM  
To write a python program to create the tuple by the multiples of 3 up to N and the print sum of the elements of the list. Get the N value from the user.

---

### ALGORITHM

1.Input the value of N from the user.

2.Initialize an empty list called multiples_list.

3.Loop variable i from 1 to N (inclusive):

4.If i is divisible by 3 (i % 3 == 0), append i to multiples_list.

5.Convert multiples_list to a tuple called multiples_tuple.

6.Calculate the sum of the elements in multiples_tuple using the sum() function.



### PROGRAM

s=eval(input())

t=()

p=0

i=0

sum=0

while p<s-3:

    i=i+1
    
    p=i*3
    
    t=t+(p,)
    
print(t)

for j in t:

    sum+=j
    
print("Sum is",sum)


### OUTPUT

![image](https://github.com/user-attachments/assets/a6141c8c-3df0-4860-8431-4663ebba218e)


### RESULT

Thus the python program to create the tuple by the multiples of 3 up to N and the print sum of the elements of the list. Get the N value from the user was successfuly written and executed.
