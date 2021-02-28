# *************************
# Esercizio 046 Pag. 34
# *************************

def chessboard():

    col = ["a","b","c","d","e","f","g","h","i"]
    row = ["1","2","3","4","5","6","7","8","9"]

    chess_map = []

    for y in col:
        for x in row:
            chess_map.append(y+x)

    white_sqr = []
    black_sqr=[]

    for sqr in chess_map:
        if chess_map.index(sqr) % 2 == 0:
            black_sqr.append(sqr)
        else:
            white_sqr.append(sqr)

    while True:

        key = input("Inserisci qui la casella di cui cercare il colore --> ")

        if "i" in key or "9" in key:
            print("Il parametro di ricerca inserito non è valido. Riprova.")
        elif key in white_sqr:
            print("La casella è bianca!")
        elif key in black_sqr:
            print("La casella è nera!")
        elif key not in white_sqr and key not in black_sqr:
            print("Il parametro di ricerca inserito non è valido. Riprova.")

        loop = input("Vuoi provare ancora? S/N --> ")
            
        if loop == "s" or loop == "S":
            continue
        elif loop == "n" or loop == "N":
            print("Grazie e a presto!!")
            break
        else:
            print("Hai inserito un'opzione non valida. Esco dal sistema. A presto!!")
            break

chessboard()
