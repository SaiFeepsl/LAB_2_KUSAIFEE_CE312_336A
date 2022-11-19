User = ["number_id","name","count"]
print(len(User))
print(User.index("name"))


User.append("status")
print("User :",User)

User2 = [["number_id","name","count"]]
print("lengh of User2: ",len(User2))

User2.insert(1,["rubber",0,"Out of stock"])
User2.insert(2,["Ruler",5,"in stock"])
User2.insert(3,["Pencil",1,"in stock"])
print("User2:",User2)
User2.insert(4,["Pen",10,"in stock"])
User2.insert(5,["Colour pencil",5,"in stock"])
User2.insert(6,["A4 Paper",0,"Out of stock"])
Stock_instock = []
Stock_outstock = []

def Createstock():
    for i in User2:
        for n in i:
            if n == 'in stock':
                Stock_instock.append(i)
                Stock_instock.sort()
            if n == 'Out of stock':
                Stock_outstock.append(i)
                Stock_outstock.sort()


def updateUser3():
    for i in Stock_instock:
        for n in i:
            if n == 'Out of stock':
                Stock_instock.pop(i)
                Stock_outstock.append(i)
                Stock_outstock.sort()
Createstock()
print("in stock",Stock_instock)
print("out of stock",Stock_outstock)

Stock_instock[3][1] = 4 #ruler
Stock_instock[0][1] = 4 #Colour Pencil
Stock_instock[2][1] = 0 #Pencil
Stock_instock[2][2] = "Out of stock" #Update
Stock_instock[1][1] = 8 #Pen
Stock_outstock.append(Stock_instock[2])
Stock_instock.pop(2)
print("stock after update ",Stock_instock)
print("stock after update ",Stock_outstock)