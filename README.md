# python-algorithm-2
program that prints all of numbers together without spaces.
import sys
n = int(sys.stdin.readline())
a = list(sys.stdin.readline())
sum = 0
for i in range(n):
    sum = sum + int(a[i])
print(sum)
