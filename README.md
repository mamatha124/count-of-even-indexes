# count-of-even-indexes in python
# count of even indexes
# Approach-1
s=(input())
c=0
for i in range(len(s)):
  if i%2==0:
    c=c+1 
print(c)

# Approach-2 by using slice
s=input()
x=s[::2]
print(len(x))

# Approach-3
s=input()
x=""
y=""
for i in range(len(s)):
  if i%2==0:
    x=x+s[i]
for i in range(len(s)):
  if i%2==0:
    y=y+s[i]
print(x+y)
