# ABC
added code
s1 = "tajareddy"
s2 = ""

for i in range(len(s1)-1,-1,-1):
	s2 = s2 + s1[i]
print(s2)

s3 = "hello"
s4 = ""

for i in s3:
    count = s3.count(i)
    if not count >= 2:
        s4 = s4+i
print(s4)

str4="ramrao"
set1=set(str4)
str=""
for i in set1:
    if str4.count(i)>=2:
        str=str+i
        
print(str)

str1="banana"
str2=str1.replace("n","a")
print(str2)
        
    
