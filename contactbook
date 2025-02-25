contacts = {}

while True:
    choice = input("\n1.Add  2.View  3.Search  4.Delete  5.Exit\nChoice: ")
    if choice == "1": contacts[input("Name: ")] = input("Phone: ")
    elif choice == "2": print("\n".join(f"{k}: {v}" for k, v in contacts.items()) or "No contacts found.")
    elif choice == "3": print(contacts.get(input("Name: "), "Not found"))
    elif choice == "4": contacts.pop(input("Name: "), print("Not found")) 
    elif choice == "5": break
    else: print("Invalid choice!")
