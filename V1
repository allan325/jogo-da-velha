a = [     
        [1,2,3], #linha 0
        [4,5,6],
        [7,8,9]
    ]

def mostrar_tabuleiro():
    
    print(f"{a[0][0]} | {a[0][1]} | {a[0][2]}")
    print("-" * 9)
    print(f"{a[1][0]} | {a[1][1]} | {a[1][2]}")
    print("-" * 9)
    print(f"{a[2][0]} | {a[2][1]} | {a[2][2]}")

def validar_jogada ():
    if j1 > 9 or j1 < 1:
      print("numero-invalido. Digite um numero de 1 a 9")
    else:
        pass
    
def validar_jogada1 ():
    if j2 > 9 or j2 < 1:
      print("numero-invalido. Digite um numero de 1 a 9")
    else:
        pass
    
def verificar_vitoria ():
     if a[0][0]  == "X" and a[0][1]  == "X" and a[0][2]  == "X" :
         print("Vitoria do X")
     elif a[1][0] == a[1][1] == a[1][2] == "X": #eu pedi para o chatgpt fazer essa parte pq seria so copiar e colar
         print("Vitória do X")
     elif a[2][0] == a[2][1] == a[2][2] == "X":
         print("Vitória do X")
     elif a[0][0] == a[1][0] == a[2][0] == "X":
         print("Vitória do X")
     elif a[0][1] == a[1][1] == a[2][1] == "X":
         print("Vitória do X")
     elif a[0][2] == a[1][2] == a[2][2] == "X":
         print("Vitória do X")
     elif a[0][0] == a[1][1] == a[2][2] == "X":
         print("Vitória do X")
     elif a[0][2] == a[1][1] == a[2][0] == "X":
         print("Vitória do X")
     elif a[0][0] == a[0][1] == a[0][2] == "O":
        print("Vitória do O")
     elif a[1][0] == a[1][1] == a[1][2] == "O":
        print("Vitória do O")
     elif a[2][0] == a[2][1] == a[2][2] == "O":
        print("Vitória do O")
     elif a[0][0] == a[1][0] == a[2][0] == "O":
        print("Vitória do O")
     elif a[0][1] == a[1][1] == a[2][1] == "O":
        print("Vitória do O")
     elif a[0][2] == a[1][2] == a[2][2] == "O":
        print("Vitória do O")
     elif a[0][0] == a[1][1] == a[2][2] == "O":
        print("Vitória do O")
     elif a[0][2] == a[1][1] == a[2][0] == "O":
        print("Vitória do O")
     
def fazer_jogada(): 
    if j1 == 1:
       a[0][0] = "X"
    elif j1 == 2:
        a[0][1] = "X"
    elif j1 == 3:
        a[0][2] = "X"
    elif j1 == 4:
        a[1][0] = "X"
    elif j1 == 5:
        a[1][1] = "X"
    elif j1 == 6:
        a[1][2] = "X"
    elif j1 == 7:
        a[2][0] = "X"
    elif j1 == 8:
        a[2][1] = "X"
    elif j1 == 9:
        a[2][2] = "X"

def fazer_jogada1(): 
    if j2 == 1:
        a[0][0] = "O"
    elif j2 == 2:
        a[0][1] = "O"
    elif j2 == 3:
        a[0][2] = "O"
    elif j2 == 4:
        a[1][0] = "O"
    elif j2 == 5:
        a[1][1] = "O"
    elif j2 == 6:
        a[1][2] = "O"
    elif j2 == 7:
        a[2][0] = "O"
    elif j2 == 8:
        a[2][1] = "O"
    elif j2 == 9:
        a[2][2] = "O"

while True:
 for i in range (8):
     mostrar_tabuleiro()
    
     j1 = int(input("Digite o numero que quer troca por X:"))
     validar_jogada()
     fazer_jogada()
     mostrar_tabuleiro()
     verificar_vitoria()
     j2 = int(input("Digite o numero que quer troca por O:"))
     validar_jogada1()
     fazer_jogada1()
     verificar_vitoria()
     
