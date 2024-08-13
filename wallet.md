def main():
    #valeur porte monnaie de Apo
    wallet = int(input("Enter your wallet value: "))
    #valeur de l'objet à acheter
    item_cost  =  int(input("Enter your item cost : "))
    #valeur porte monnaie après l'achat
    wallet_new = wallet - item_cost
    print("Your wallet value is now: ",wallet_new,"chf" )


    if wallet_new < 0:
        print("YOU'RE POOR ")

if __name__ == '__main__':
    main()
