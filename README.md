# random_password_generator
import random
import string

print("Random password generator")

#length_of_passsword
length=int(input("Enter the length of password: "))

#considering_characters
lowerC=string.ascii_lowercase
upperC=string.ascii_uppercase
digitD=string.digits
symbolsD=string.punctuation

#cominations_of_characters
all=lowerC+upperC+digitD+symbolsD
password="".join(random.sample(all,length))

#print_password
print(password)
