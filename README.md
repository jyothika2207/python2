
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


#set operations
my_set={1,2,3,4,5,6}
print(my_set)
print("Add and remove values")
my_set.add(7)
print(my_set)
my_set.remove(2)
print(my_set)
my_set.discard(5)
print(my_set)
print("Membership check")
print(1 in my_set)
print(10 in my_set)


#operations
print("Union")
a={1,2,3,4,5,6,7,8}
b={3,4,5,6,7,9,10}
print(a.union(b))
print(a.intersection(b))
print("Difference")
print(a.difference(b))
print("symmetric Difference")
print(a.symmetric_difference(b))
