# linear-search-python
def search(l,key):
    for i in range(len(l)):
        if key== l[i]:
            print("key element at index:",i)

        #else:
            #print("element not found")
num=int(input("list lemgth"))
l=[int(input()) for i in range (num)]
print(l)
key=int(input("enter key element"))
search(l,key)
