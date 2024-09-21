# PR9_WHILE_LOOP.3W

#Practica 9 de la función 

#While

#Ejemplo principal

#Imprimir líneas en blanco y un título para la práctica

print("")  #Imprime una línea en blanco

print("Esta es mi práctica 9 de while")  #Título de la práctica

print("")  #Imprime otra línea en blanco

print("Jimenez Gamboa Issis Alexa 3W")  #Nombre y grupo del autor

print("")  #Imprime una línea en blanco

# Inicializa la variable i en 1
i = 1

#Inicia un bucle while que se ejecuta mientras i sea menor que 6

while i < 6:

    #Imprime el valor actual de i
    
    print(i)
  
    # Incrementa i en 1
    
    i += 1
    
#Este bloque se ejecuta después de que finaliza el bucle while
else:

    #Imprime un mensaje indicando que i ya no es menor que 6
    
    print("i ya no es menor que 6")
    
print("")
print("")

#Ejemplo 1

# Inicializamos la suma en 0

suma = 0

# Pedimos al usuario que ingrese un número

numero = int(input("Ingresa un número (0 para salir): "))

# Usamos un bucle while que continuará hasta que el usuario ingrese 0

while numero != 0:

    suma += numero  # Agregamos el número a la suma
    
    numero = int(input("Ingresa otro número (0 para salir): "))  # Pedimos otro número

# Imprimimos la suma total

print("La suma total es:", suma)

![image](https://github.com/user-attachments/assets/309cbed7-8075-47fa-b37a-c5bbf210a7f3)
