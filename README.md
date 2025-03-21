# Finding-the-multiples-of-a-number-not-more-than-50
This code is used to find the multiples of a number and also to find the number of multiples of that number not more than a range of 50 
num = input("Enter a number : ")
while len(num)==0 or not num.isdigit():
     num = input("Enter a number : ")
num = int(num)
factor_count = 0
for i in range(1,51):
     if i % num ==0:
          print(f"{i} is a multiple of {num}")
          factor_count += 1
print(f"The number of multiples are : {factor_count}")
