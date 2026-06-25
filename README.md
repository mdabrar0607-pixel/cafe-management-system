# cafe-management-system
menu={
    "pizza":52,
    "burger":85,
    "salad":50,
    "fries":40,
    "chicken":40,
}
print("WELCOME TO PYTHON CAFE")
print("HOTEL MENU")
print("pizza is ",menu["pizza"])
print("burger is ",menu["burger"])
print("salad is ",menu["salad"])
print("fries is ",menu["fries"])
print("chicken is ",menu["chicken"])


total_order=0
item_1=input("enter your order ")
if item_1 in menu:
    total_order =+ menu[item_1]
    print("your item is ",item_1)
else:
    print("your item is not in menu")

another_order=input("do you want to add  another item(yes/no): ")
if another_order == "yes":
 item_2=input("enter your 2nd order ")
if item_2 in menu:
    total_order =+ menu[item_2]
    print("your item is ",item_2)
else:
    print("your item is not in menu")
print("total order is ",total_order)

