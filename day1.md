### input 

```
name = input("Enter your name: ")
print("Hello", name)
```


### input in **int**
```
num1 = int(input("Enter a number: "))
num2 = input("Enter another number: ")

sum = (num1 + int(num2))

print("addition is:",sum) 
```

---

### Control structure 

#### if-else basic program 
```
age = int(input("Enter your age: "))
if age >= 18 :
    print("You can VOTE")
else:
    print("You can not VOTE")
```

---

#### elif basic program 
```
marks = int(input("Enter your marks "))
if marks >= 85 :
    print("Grade A+")
elif marks >= 80 :
    print("Grade A")
elif marks >= 70 :
    print("Grade B")
elif marks >= 50 :
    print("Grade C")
elif marks >= 40 :
    print("Grade D")
else :
    print("FAIL")
```

---
```
cpu_usage= int(input("Enter CPU usage: "))
if cpu_usage >= 70 :
    print("CRITICAL: very high")
elif cpu_usage >= 50 :
    print("WORKING: normal")
else :
    print("Good")
```

---

