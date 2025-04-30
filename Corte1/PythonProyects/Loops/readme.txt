for i in range(100, 301):      # Recorre los números del 100 al 300
    if (i % 12) != 0:          # Si el número no es divisible entre 12
        continue               # Salta al siguiente número
    print(i)                   # Imprime el número si es múltiplo de 12

