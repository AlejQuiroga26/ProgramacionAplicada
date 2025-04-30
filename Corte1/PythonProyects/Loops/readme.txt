for i in range(100, 301):    #Método FOR que recorre de 101 a 300
    if (i%12) != 0:          #Condicional para los modulos diferetes a 0 
        continue             #Solo captura los numeros sin residuo al dividir por 12
    print(i)                 #Imprime el múltiplo
