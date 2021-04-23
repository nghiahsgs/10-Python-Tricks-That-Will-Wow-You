# 10-Python-Tricks-That-Will-Wow-You
10 Python Tricks That Will Wow You

## 1. Condition Inside the print Function
```
print("odd" if int(input("Enter a num: "))%2 else "even")
```

## 2. Conditional List — All
```python
score=325
wickets=7
catch=4
list_cond=[score>320,
           wickets<8,
           catch>3]
if(all(list_cond)):
    print("Pranjal Saxena")
else:
    print("Lose")
```

## 3. Conditional List — Any
```python
score=200
wickets=7
catch=4
list_cond=[score>320,
           wickets<8,
           catch>3]
if(any(list_cond)):
    print("Win")
else:
    print("Lose")
```

## 4. Multiple Inputs in One Go
```python
a,b,c=input("Enter three inputs ").split()
```

## 5. Swap Like a Pro
```python
salary=85000
exp=3
salary,exp=exp,salary
print(exp)
```

## 6. Take Out the Duplicate Data
```python
li=[1,5,8,6,5,9,6,9,5,6,9,6,5,4]
print(list(set(li)))
```

## 7. Most Repeated Object
```python
li=[1,5,8,6,5,9,6,9,5,6,9,6,5,4,"a","a","b","b","a","a","a"]
print(max(set(li), key=li.count))
```
## 8. Magic of List Comprehension
```python
li=[i**3 for i in range(1,15) if i%2==0]
print(li)

li=[i**3 if i%2==0 else 0 for i in range(1,15)]
print(li)
```


## 9. Infinite Input Arguments
```python
def fun1(*a):
    print(a)
ans=fun1(5,6,9,6,9,6,6)
```
## 10. Reverse Like a Pro
```python
name="Pranjal Saxena"
print(name[::-1])
```

ref https://betterprogramming.pub/10-python-tricks-that-will-wow-you-de450921d96a
