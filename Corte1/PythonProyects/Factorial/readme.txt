while True:  # Bucle infinito

    value = int(input("Enter a positive integer value: "))        # Pide un entero
    print("Value:", value)                                        # Muestra el valor ingresado
    
    if value > 0:                                                 # Verifica si el número es positivo
        fact = 1                                                  # Inicializa el factorial
        for i in range(1, value + 1):                             # Recorre del 1 al valor
            fact *= i                                             # Multiplica para calcular el factorial
        print(f'The factorial of {value} is:', fact)              # Muestra el resultado
    else:
        print("Please, enter a positive integer number")          # Mensaje de error si es negativo o cero
