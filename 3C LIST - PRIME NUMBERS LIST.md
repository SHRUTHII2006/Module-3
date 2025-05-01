# Exp.No:3c
## LIST - PRIME NUMBERS LIST


### AIM  

To write a python program to create a list contains the prime numbers upto N values and print the reverse of the list.


### ALGORITHM

1.Input the value of N.

2.Initialize an empty list called prime_list.

3.Loop i from 2 to N:

4.For each i, check if it's a prime:

5.A number i is prime if it is not divisible by any number from 2 to sqrt(i).

6.If i is prime, append it to prime_list.

7.Reverse the list using slicing or built-in methods.

8.Print the reversed list.



### PROGRAM

def is_prime(num):

    if num < 2:
    
        return False
        
    for i in range(2, int(num ** 0.5) + 1):
    
        if num % i == 0:
        
            return False
            
    return True

def prime_numbers_upto_n(N):

    primes = [num for num in range(2, N + 1) if is_prime(num)]
    
    return primes

N = int(input())

prime_list = prime_numbers_upto_n(N)

print(prime_list[::-1])


### OUTPUT


![image](https://github.com/user-attachments/assets/563d9b42-3f3a-458a-912e-57ddfaa404af)



### RESULT

Thus the python program to create a list contains the prime numbers upto N values and print the reverse of the list aws successfuly executed.
