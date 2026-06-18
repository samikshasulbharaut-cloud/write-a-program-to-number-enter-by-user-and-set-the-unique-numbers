#1st method 

friends={
    "sameer":input("enter your favorite fruit: "),
    "vishal":input("enter your favorite fruit: "),
    "mira":input("enter your favorite fruit: "),
}
print(friends)
#in first program only value are entered by user 

#2nd method

d={}
name= input("Enter your name: ")
lang=input("Enter your favorite language :")
d.update({name:lang})
name= input("Enter your name: ")
lang=input("Enter your favorite language :")
d.update({name:lang})
name= input("Enter your name: ")
lang=input("Enter your favorite language :")
d.update({name:lang})
name= input("Enter your name: ")
lang=input("Enter your favorite language :")
d.update({name:lang})
print(d)
#here the key and value both are entered by user
