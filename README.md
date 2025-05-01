# 19CS301Module8
### EXP NO.8a Find the amount

### Aim: 
To calculate the final amount paid by Vimla for a microwave oven after applying a 5% discount and adding 2% CST.

### Algorithm:

1.	Initialize the price of the microwave oven.
2.	Calculate the discount amount (5% of price).
3.	Calculate the CST amount (2% of price).
4.	Compute the final amount using the formula:
            Final amount = price + CST - discount
5.	Display the final amount.



### Program:
```
#Reg.NO:212222040120
#Name:PRASANNA R
amount=25000
discount_percentage=5
cst_percentage=2
discount_amount=(discount_percentage/100)*amount
cst_amount=(cst_percentage/100)*amount
final_amount=amount+cst_amount-discount_amount
print(final_amount)
```
### Output:
![LAB8 DAY1](https://github.com/user-attachments/assets/1e5c2314-d532-4a8a-a98b-0d63a6813499)


### Result: 
Thus, the given program is implemented and executed successfully .

### EXP NO.8b Construct a pattern of asterisks in an increasing and then decreasing triangle form

### Aim: 
To construct a pattern of asterisks in an increasing and then decreasing triangle form based on a given value of n.

### Algorithm:
1.	Accept an integer n from the user.
2.	Use a for loop to print the first half of the pattern (increasing).
3.	Use another for loop to print the second half of the pattern (decreasing).
4.	Each line should print i asterisks separated by spaces.

### Program:
```
#Reg.NO:212222040120
#Name:PRASANNA R
n=int(input())
for i in range(1, n+1):
    print('* ' * i)
for i in range(n-1, 0, -1):
    print('* ' * i)
```
### Output:
![LAB8 DAY2](https://github.com/user-attachments/assets/e8188873-28c8-427f-b840-c8c61cd49da5)

### Result: 
Thus, the given program is implemented and executed successfully .
 

### EXP NO.8c Find the runner-up (second highest) score from a list of integers entered by the user
### Aim: 
To find the runner-up (second highest) score from a list of integers entered by the user.

### Algorithm:
1. Prompt the user to input a list of integers.
2. Convert the input string into a list of integers.
3. Remove duplicates from the list (since the runner-up needs to be distinct).
4. Sort the list in descending order.
5. Print the second highest value (the runner-up).

### Program:
```
#Reg.NO:212222040120
#Name:PRASANNA R
n=int(input())
arr=list(map(int, input().split()))
max_score=max(arr)
arr=[x for x in arr if x != max_score]
runner_up=max(arr)
print(runner_up)
```
### Output:
 
![image](https://github.com/user-attachments/assets/5612bdc8-79b8-458c-a858-137f166b28db)

### Result: 
Thus, the given program is implemented and executed successfully .
 


### EX: 8d Develop a Python program that counts the number of vowels and consonants in a given string.
### Aim:
To develop a Python program that counts the number of vowels and consonants in a given string.

### Algorithm:
1.	Define a function fun(s) that takes a string as input.
2.	Initialize two counters for vowels and consonants.
3.	Traverse each character in the string:
      -	If it is an alphabet, check if it's a vowel (a, e, i, o, u).
      -	If yes, increment the vowel counter.
      -	Otherwise, increment the consonant counter.
4.	Print the total number of vowels and consonants.

### Program:
```
#Reg.NO:212222040120
#Name:PRASANNA R
def fun(s):
    v,c=0,0
    for i in s:
        if i in ['A','E','I','O','U','a','e','i','o','u']:
            v+=1
        else:
            c+=1
    print(f"Number of Vowels: {v}")
    print(f"Number of Consonants: {c}")
s=input()
```
### Output:

![image](https://github.com/user-attachments/assets/f9702eb8-7524-4e4d-a8c6-7861024a6720)


### Result: 
Thus, the given program is implemented and executed successfully .
 


