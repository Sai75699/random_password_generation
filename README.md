# random_password_generation
import random
password="ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789abcdefghijklmnopqrstuvwxyz~!@#$%^&*+(_}{)"
length_password=int(input("Enter the length of the password:"))
a="".join(random.sample(password,length_password))
print(f"your password is {a}")
