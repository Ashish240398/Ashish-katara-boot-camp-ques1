# Ashish-katara-boot-camp-ques1
#Python program to generate md 5 of any string 



import hashlib

str = input("Enter string : ") 

md5_value = hashlib.md5(given_str)
md5_value_2 = hashlib.md5(given_str_2)

print(md5_value.hexdigest())
