# Exp.No:3c
## LIST - REVERSE MEMBERS LIST



### AIM  
To write a python program to reverse the members of a given list.


 ALGORITHM
 
1.Begin the program.

2.Input the elements of the list from the user (or define a list directly).

3.Use a built-in method or slicing to reverse the list:

Option 1: Use list.reverse() method.

Option 2: Use slicing list[::-1].

4.Print the reversed list.

5.Terminate the program.


 PROGRAM
 
n=int(input())

input_list=[]

for i in range(0,n):

    input_list.append(int(input()))
    
for i in range (n//2):

    temp=input_list[i]
    
    input_list[i]=input_list[n-i-1]
    
    input_list[n-i-1]=temp
    
print(input_list)


 OUTPUT

![image](https://github.com/user-attachments/assets/762de86f-73ef-4dd8-908a-093496b1218f)

 

 RESULT
Thus the  python program to reverse the members of a given list was implemented and executed successfully.
