"""
thislist = ["avocado", "pineapple", "mango"]
thislist.reverse()
print(len(thislist))
print(type(thislist))

list1 = ["abc", 34, True, 40, "male"]
print(type(list1))

numbers = [1,2,3,4,5]
numbers.reverse()
print(numbers)
print(thislist)


print(thislist[0])
print(thislist[1])
print(thislist[-1])
print(thislist[0:2])
print(thislist[:2])
"""
"""
if "mango" in thislist:
    print("I love apple")
else:
    print("No mango")


thislist[1] = "Mango"
print(thislist)

thislist[1:2] = ["pineapple", "avocado","Kiwi", "mango", "Strawberry"]
print(thislist)

thislist[1:3] = ["Lamb"]
print(thislist)


thislist.append("Mango")
thislist.insert(1,"Mango")
thislist.remove("Mango")
thislist.pop(1)
thislist.pop()
thislist.clear()
print(thislist)
"""
thislist = ["avocado", "pineapple", "mango"]
thislist.reverse()
print(thislist)
thislist.append("Mango")
print(thislist)
thislist.insert(1,"Mango")
print(thislist)
thislist.remove("Mango")
print(thislist)

thislist = ["banana", "pawpaw", "mango"]
thislist.pop(1)
print(thislist)
thislist.pop()
print(thislist)
thislist.extend(["Mango", "Pineapple"])
print(thislist)

thislist =["book","pencil","pen","eraser","pencil case","pen"]
thislist.sort()
print(thislist)
thislist.count("pen")
print(thislist.count("pen"))
thislist.copy()
print(thislist)
thislist.index("pen")
print(thislist.index("pen"))
thislist.clear()
print(thislist)
