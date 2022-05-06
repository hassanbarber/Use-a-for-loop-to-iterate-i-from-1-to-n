# Use-a-for-loop-to-iterate-i-from-1-to-n
Write a program to create a dictionary containing (i, i*i), where i is an integer from 1 to n (including 1 and n), n is entered from the keyboard. Then print this dictionary to the screen. Example: Assuming number n is 8, the output will be: {1:1, 2:4, 3:9, 4:16, 5:25, 6:36, 7:49, 8:64}.
n = int(input("Enter a positive integer n = "))
 
d = dict()
for i in range(1, n + 1):
     d[i] = i * i
 
print(d)
