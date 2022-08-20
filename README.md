import random
length = input("Enter the length of password")
def printRandomString(n):
    MAX = 25
    alphabet = ['a', 'b', '@','!' , '1','2','4','8','#' 'c', 'd', 'e', 'f', 'g',
                'h', 'i', 'j', 'k', 'l', 'm', 'n',
                'o', 'p', 'q', 'r', 's', 't', 'u',
                'v', 'w', 'x', 'y', 'z']
    res = ""
    for i in range(n):
        res = res + alphabet[random.randint(0, MAX)]
    return res
n = int(length)
print(printRandomString(n))
