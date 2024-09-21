# trabajo_de_classroom
crear un código que verifique que el numero que ingresa el usuario si es par, impar o 0

print(" ")

print("Ramirez Torres Angel Manuel 3°W trabajo_de_classroom")

print(" ")

print("INSTRUCCIONES:")

print("crear un código que verifique que el numero que ingresa el usuario si es par, impar o 0")

numero = input("Ingresa un numero entre el 0 y el 30:     ")#Hay que ingresar la variable que pide

num =int(numero)

x = [2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30]#Declaramos variables con el valor de "x"

y = [1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21, 23, 25, 27, 29,]#Declaramos variables con el valor de "y"

z = [0]#Declaramos variables con el valor de "z"

if num in x: #Aqui empieza el proceso para saber si es par, impar o 0

    print("El numero ingresado es par")#Se cumple la condicion en la primera etapa 

elif num in y:#Nos dice que la etapa anterior fue falsa

    print("El numero ingresado es impar")#Se cumple la condicion en la segunda etapa

elif num in z:#Nos dice que la etapa anterior fue falsa

    print("El numero ingresado equivale a 0")#Se cumple la condicion en la tercera etapa

else:#De lo contrario

    print("-NO INGRESASTE UN NUMERO COMO TAL- O - EL NUMERO INGRESADO ESTA FUERA DEL RANGO PERMITIDO-")

![image](https://github.com/user-attachments/assets/af6ad409-968d-43bf-a58e-ecf6fddc227b)
![image](https://github.com/user-attachments/assets/21cba884-304d-46fa-87d3-35c162d91f4f)
