import sys 
import re
from colorama import Back 
import datetime
regex = '^[a-z0-9]+[\._]?[a-z0-9]+[@]\w+[.]\w{2,3}$'


def initial_phonebook():   
    rows, cols = int(input("Please enter initial number of contacts: ")), 5  
    phone_book = [] 
    print(phone_book) 
    for i in range(rows): 
        print("\nEnter contact %d details in the following order (ONLY):" % (i+1)) 
        print("NOTE: * indicates mandatory fields") 
        print("....................................................................") 
        temp = [] 
        for j in range(cols): 
                      
            if j == 0: 
                temp.append(str(input("Enter name*: "))) 
                if temp[j] == '' or temp[j] == ' ': 
                    sys.exit("Name is a mandatory field. Process exiting due to blank field...") 
                                   
            if j == 1: 
                temp.append(int(input("Enter number*: "))) 
                if(len(str(temp[j])) != 10):
                    print(Back.RED, "Phone number should be of 10 Digit, please enter valid phone number for Record ")
                    print(Back.BLACK)
                    sys.exit()
                                 
            if j == 2: 
                temp.append(str(input("Enter e-mail address: "))) 
                if temp[j] == '' or temp[j] == ' ': 
                    temp[j] = None
                else:
                    if(re.search(regex,temp[j])):
                       print()
                    else:
                        print(Back.RED,"Invalid email")
                        print(Back.BLACK)
                        sys.exit()

                      
            if j == 3: 
                temp.append(str(input("Enter date of birth(yy-mm-dd): "))) 
                if temp[j] == '' or temp[j] == ' ': 
                    temp[j] = None
                else:
                    datetime.datetime.strptime(temp[j],'%Y-%m-%d')
            if j == 4: 
                temp.append(str(input("Enter category(Family/Friends/Work/Others): "))) 
                if temp[j] == "" or temp[j] == ' ': 
                    temp[j] = None
                      
        phone_book.append(temp)       
   
    print(phone_book)
    return phone_book 
  
def menu(): 
    print("********************************************************************") 
    print("\t\t\tSMARTPHONE DIRECTORY", flush=False) 
    print("********************************************************************") 
    print("\tYou can now perform the following operations on this phonebook\n") 
    print("1. Add a new contact") 
    print("2. Remove an existing contact") 
    print("3. Delete all contacts") 
    print("4. Search for a contact") 
    print("5. Display all contacts") 
    print("6. Add Reminder")
    print("7. Exit phonebook") 
  
    choice = int(input("Please enter your choice: ")) 
      
    return choice 
  
def add_contact(pb): 
    dip = [] 
    for i in range(len(pb[0])): 
        if i == 0: 
            dip.append(str(input("Enter name: "))) 
        if i == 1: 
            dip.append(int(input("Enter number: "))) 
            if(len(str(dip[i])) != 10):
                print(Back.RED,"Enter valid phone number.")
                print(Back.BLACK)
                sys.exit()
        if i == 2: 
            dip.append(str(input("Enter e-mail address: "))) 
            if(re.search(regex,dip[i])):
                print()
            else:
                print(Back.RED,"Entered email is not valid.")
                print(Back.BLACK)
                sys.exit()
        if i == 3: 
            dip.append(str(input("Enter date of birth(YY-MM-DD): "))) 
            if(datetime.datetime.strptime(dip[i],'%Y-%m-%d')):
                print()
            else:
                print("Entered DOB is not correct.")

        if i == 4: 
            dip.append(str(input("Enter category(Family/Friends/Work/Others): "))) 
    pb.append(dip) 
    return pb 
  
def remove_existing(pb): 
    query = str(input("Please enter the name of the contact you wish to remove: ")) 
    temp = 0      
    for i in range(len(pb)): 
        if query == pb[i][0]: 
            temp += 1           
            print(pb.pop(i)) 
            print("This query has now been removed")               
            return pb 
    if temp == 0: 
        print("Sorry, you have entered an invalid query.\Please recheck and try again later.")  
        return pb 
  
def delete_all(pb): 
    return pb.clear() 
  
def search_existing(pb): 
    choice = int(input("Enter search criteria\n\n\ 1. Name\n2. Number\n3. Email-id\n4. DOB\n5. Category(Family/Friends/Work/Others)\\nPlease enter: "))  
    temp = [] 
    check = -1  
    if choice == 1:  
        query = str(input("Please enter the name of the contact you wish to search: ")) 
        for i in range(len(pb)): 
            if query == pb[i][0]: 
                check = i 
                temp.append(pb[i]) 
                  
    elif choice == 2: 
        query = int(input("Please enter the number of the contact you wish to search: ")) 
        for i in range(len(pb)): 
            if query == pb[i][1]: 
                check = i 
                temp.append(pb[i]) 
                  
    elif choice == 3: 
        query = str(input("Please enter the e-mail ID\of the contact you wish to search: ")) 
        for i in range(len(pb)): 
            if query == pb[i][2]: 
                check = i 
                temp.append(pb[i]) 
                  
    elif choice == 4: 
        query = str(input("Please enter the DOB (in dd/mm/yyyy format ONLY)\of the contact you wish to search: ")) 
        for i in range(len(pb)): 
            if query == pb[i][3]: 
                check = i 
                temp.append(pb[i]) 
                  
    elif choice == 5:  
        query = str(input("Please enter the category of the contact you wish to search: ")) 
        for i in range(len(pb)): 
            if query == pb[i][4]: 
                check = i 
                temp.append(pb[i])           
    else: 
        print("Invalid search criteria") 
        return -1
      
    if check == -1: 
        return -1
        
    else: 
        display_all(temp) 
        return check 
       
def display_all(pb): 
    if not pb: 
        print("List is empty: []") 
    else: 
        for i in range(len(pb)): 
            print(pb[i]) 
  
def thanks(): 
    print("********************************************************************") 
    print("Thank you for using our Smartphone directory system.") 
    print("Please visit again!") 
    print("********************************************************************") 
    sys.exit("Goodbye, have a nice day ahead!") 

def add_reminder(pb):
    import time
    ask = str(input("To whom you want to send the Reminder, mention the Name: "))        
    print("What shall I remind you about?")
    text = str(input())
    print("In how many minutes?")
    local_time = float(input())
    local_time = local_time * 60
    time.sleep(local_time)
    print(Back.RED + ask," I am here to remind you about ",text)
    print(Back.BLACK)
    

# Main function code 

print("....................................................................") 
print("Hello dear user, welcome to our smartphone directory system") 
print("You may now proceed to explore this directory") 
print("....................................................................") 

ch = 1
pb = initial_phonebook() 
while ch in (1, 2, 3, 4, 5, 6): 
    ch = menu() 
    if ch == 1: 
        pb = add_contact(pb) 
    elif ch == 2: 
        pb = remove_existing(pb) 
    elif ch == 3: 
        pb = delete_all(pb) 
    elif ch == 4: 
        d = search_existing(pb) 
        if d == -1: 
            print("The contact does not exist. Please try again") 
    elif ch == 5: 
        display_all(pb) 
    elif ch == 6:
        pb = add_reminder(pb)
    else: 
        thanks() 
