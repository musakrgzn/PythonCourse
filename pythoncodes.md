#PYTHON

##VARIABLES
name = "musa" ; print(name)     ##musa## 
x = str(3)
y = int(3)
z= float(3) ; print(x, y, z) ##3 3 3.0##
x = 5
y = "John"
print(type(x))  ##class 'int'
print(type(y))  ##class 'str'
print(isinstance(x, int)) ##true 


##DATATYPE
fruits = ["apple", "banana", "cherry"] #list
x, y, z = fruits
print(x, y, z) ##apple banana cherry
print(fruits[2]) ##cherry

t = ("apple", "banana", "cherry") #tuple
print(t) ##('apple', 'banana', 'cherry')

d = {"name" : "John", "age" : 36} #dict
print(d)
print(d["name"]) #John

s = {"apple", "banana", "cherry"} #set
print(s) ##{'banana', 'cherry', 'apple'}

##OPERATORS
age = 8
age *= 5
print(age) ##40

##STRINGS

name = "atom"
phrase = name + " is my name"
print(phrase) ##atom is my name

z = "bmg"
z += " is my name" ; print(z) ##bmg is my name

print("bmg".upper()) ##BMG
print("BMG".lower())##bmg
print("BmG bmg".title())##Bmg Bmg
print("bmg".islower())##True
name = "Bioinformatics"
print(len(name))##14

name = "Bio\nLab"
print(name) ##Bio
            ##lab




