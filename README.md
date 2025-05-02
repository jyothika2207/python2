#basic logic programs
a=1
b=2
a=a^b
b=a^b
a=a^b
print(a,b)


# nested tuple
nest=((1,2),('a',7),(5,6))
print(nest[1])
print(nest[1][0])

#dictionary operations
person={'name':'jyothika','age':19,'city':'vijayawada'}
print(person)
print("accesing and modifiying the persons age:")
person['age']=15
print(person)
print("adding and removing items")
person['email']="jyothikakoliki22@gmail.com"
print(person)
print("all keys and values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
