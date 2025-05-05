# Definición de la clase Dog
class Dog:
    species = "Canis familiaris"  # Atributo de clase (compartido por todas las instancias)

    # Método constructor (inicializador de instancia)
    def __init__(self, name, age):
        self.name = name  # Atributo de instancia para el nombre
        self.age = age    # Atributo de instancia para la edad

    # Método de instancia para describir al perro
    def description(self):
        return f"{self.name} is {self.age} years old"

    # Método de instancia para hacer que el perro hable
    def speak(self, sound):
        return f"{self.name} says {sound}"

# Creación de instancias de la clase Dog
miles = Dog("Miles", 4)
buddy = Dog("Buddy", 9)

# Ejemplos de llamadas a métodos
print(miles.description())  # 'Miles is 4 years old'
print(miles.speak("Woof Woof"))  # 'Miles says Woof Woof'
print(miles.speak("Bow Wow"))  # 'Miles says Bow Wow'

# Lista de nombres de perros (sin uso en el código, pero impresa)
names = ["Miles", "Buddy", "Jack"]
print(names)  # ['Miles', 'Buddy', 'Jack']

# Imprimir una instancia de Dog (usando el método description)
print(miles)  # 'Miles is 4 years old'

