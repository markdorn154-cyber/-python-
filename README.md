# -python-
Программа вычисления среднеквадратического отклонения на python  
import math 
 
a = input().split()
b = list(map(int, a))
sum = sum(b)
sa = sum / len(b)
ber = 0
for i in b : 
    ber +=(i - sa)**2
nez = len(b)- 1
form = math.sqrt(ber / nez)
print(form)
