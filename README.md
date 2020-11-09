# S50947
First question
def countBits(n):
    count = 0
    while (n):
        count += n & 1
        n >>= 1
    return count    

value = input("Enter integer value:")
i = int(value)
print(countBits(i))
