# greed1


# 공포도 문제 

n=int(input())
data= list(map(int,input().split()))
data.sort()
result=0
count=0
print(data)
for i in data:
    count+=1
    if count>=i:
        result+=1
        count=0

print(result)
        
   
