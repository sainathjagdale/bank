# bank
bank project
def deposit():
    while (True):
       amount=(input("enter amt $:"))
       if amount.isdigit():
         amount=int(amount)
         if amount>0:

            print("deposit successfully={}".format(amount))
            break


         else:
            print("insufficient amount---try again")
       else:
         print("plz enter number:")
    return amount
#main program
deposit()
