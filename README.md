
# python-toturial 

001.py

```python 
name   = input("enter your name :")
city = input("enter your city :")

print("hello " + name )
print("you live in " + city)

age = int( input("enter your age") )

print("your age in 2030 is : " + str(age + 6) )
```

003.py

```python
#name=input ("enter your name" )
#print (name)

                          
age =('24')
future =  int(age)  + 6  #لتحويل  العمر 
 
# print future age
print ( f"  furure age {future} " )

```
اكواد مهمة 

```python
age = int("45")  # لتحويل النص الي رقم 

print(type(age))  # لمعرفة نوع المتغير

age = str(24)  # لتحويل الرقم الي نص

print(type(age))  # لمعرفة نوع المتغير

```

if part 1 

```python
# لو الامتحان  من  100  درجة لو الطالب د رجته   فوق الخمسين  يكون ناجح


# if score >= 50 :
#     print("your are success")

# if score < 50  :
#     print("your are fail")


#  >    <     <=     >=    !=



# if score >= 50 :    
#     print("success")
#     print("congrtulation")
# else :
#     print("fail")

# if لو   وبعدها شرط 
#else وإلا   بتحقق في حالة فشل كل  الشروط
#elif لاضافة شرط اخر 


score = 49

if score >= 90 :
    print("excellent")
elif score >= 80 :
    print("very good")
elif score >= 70 :
    print("good")
elif score>= 50 :
    print("satisfied")   # مقبول
else :
    print("failed")    #راسب


```

if part 2 

```python
arabic = 40
math = 60

if arabic >= 50 and math >= 50 :
    print ("you are sccuss")
else:
    print("you are faild")

```

game (  "خمن الرقم " )

```python

# لعبة تخمين الرقم 

import random
# مكتبة الارقام العشوائية

num = random.random() * 5

num1 =  int( num )    # computer 

num2 = input("guess the number : ")  # user 

print( f" computer is   : {num1}   ---  user is : {num2} " )

# if num1 == int(num2) :
#     print("you are won !")
# else :
#     print (" you are lose % the ture number is " , str(num1) ) 


```
