
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
#if 1
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
# game

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

and or 

```python

fan =  3     # مروحة
condition = 0   #  التكييف 
lamp = 2      # اضائة اللمبات

# if fan > 3 :
#     print(" area true ")  # الحجرة جيدة التهوية
# else : 
#     print ( " area false " ) # المكان سئ التهوية


if ( fan >= 3 or condition >= 1 ) and lamp >= 3  :
    print(" area true ")  # الحجرة جيدة التهوية
else : 
    print ( " area false " ) # المكان سئ التهوية


```

```python

c = 8 / 3 

print(c)

x = 8 % 3    # mod   باقي القسمة 

print(x)


#الرقم الزوجي والفردي

num = 15

if num % 2 == 1 :      ##  الشرط في حالة باقي القسمة علي 2 بيساوي 1 اي الرقم فردي
    print ("number is odd")     # فردي
else :
    print ("number is even ")   # زوجي
 

total1 =   2 +  3 +  4  * 4 
total2 = ( 2 +  3 +  4 ) * 4 

print(total1)
print(total2)

# 2 ** 3   # 2 مضروبة في نفهسا 3 مرات 

# 1    (  )
# 2    **  *   /   %   
# 3    +   -


name = "nourhan"

for x in range(5) :
    print(name)


# للتكرار
for x in range(5) :

    print(f" {x+1} {name} ")


```

list مصفوفات 
```python


fruits = [ "apple" , "banana" , "orange" , "Qiwi" , "mango"]

fruits[0] = "Sweet" 

print(fruits[0])

print(fruits)


#   في لغة البيثون يبدأ العد من الصفر
# وليس من الواحد

print(type(fruits))

print(type(fruits[0]))

print(   type(  fruits[3]   )   )  # index


# print( len(fruits)  )

for x in fruits :
    print(x)


total = len(fruits)

# print(total)

for x in range(total):
    print(  fruits[x] )



```

# function.py

```python
# print("hello")

# import random
# print(random.random())


def greeting(): # def لتعريف اي دالة 
    print("hello form code")

def days_of_year():
    print("365")

def hello(name):
    print("hello form hello function " + name)


winner = "khaled" # الفائز

hello(winner)


# greeting()
# days_of_year()
# greeting()
```
# fun2.py

```python

def score(name , myscore):
    print("your name is " + name + " score is " + str(myscore) )
    if myscore > 50 :
        print(name + " pass the test")
    else:
        print(name + "you fail the test")
    

name = "nourhan"
arbic = 95

score(name,arbic)
    
# score("nourhan" , 95 )
```
# fun 3 .py

```python

# def hallo (name ,age):
#     print("hallo "+name+str (age))
#     print(str (age))
# hallo("norhan ",25)

# for x in range(5):
#     print(x)

i = 1 # العداد
while ( i <= 20  ):       # تكرار حتي while
        print(i)
        i = i + 1

```
# str.py
```python
def naming(name):

    total = len (name)

    for x in range(total) :
        
        letter = name[x]

        if x == 0:
            letter = str.capitalize(name[x])  ## لتحويل الحرف الي حرف كبير كابيتال 
            
        print( str(x+1) + "   " +  letter  )

name = "nourhan"

naming(name)



```
