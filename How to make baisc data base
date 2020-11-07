import random
import string
typeU =int(input("Enter user type "))
length =int(input("length of user: "))
file = open('username.txt', 'w')
if typeU == 4:
    user = string.ascii_lowercase + string.digits
    le = 1
    while le < length:
        file.write(''.join(random.choice(user) for i in range(4))+'\r\n')
        le += 1
file.close()
