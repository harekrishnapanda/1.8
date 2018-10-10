'''
A Python Program to print the given string in the format specified in the sample
output.
WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a
SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all
its citizens
Sample Output:
WE, THE PEOPLE OF INDIA,
having solemnly resolved to constitute India into a SOVEREIGN, !
SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC
and to secure to all its citizens:
'''

str= "WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a \
SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all \
its citizens"

spl = str.split()

str1= " ".join(spl [0:5])  +' \n \t'+ " ".join(spl [6:14]) \
+' ! \n \t \t'+ " ".join(spl [15:19])  +' \n \t \t '+ " ".join(spl [20:]) +':'

print(str1)
