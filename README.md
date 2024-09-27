# Sepulveda_Gonzalez_Angel_Alejandro_1215

# Descripción:
# Este programa solicita al usuario su apellido paterno, apellido materno, primer nombre y segundo nombre.
# Luego muestra esta información en su formato original, y finalmente la muestra en mayúsculas.

# Entrada de datos
apelli_paterno = input("Apellido paterno: ")
apelli_materno = input("Apellido materno: ")
nombre = input("Primer nombre: ")
nombre2 = input("Segundo nombre: ")

# Guardar los datos en una lista
con = [apelli_paterno, apelli_materno, nombre, nombre2]

# Imprimir los datos individuales
print("------------------------------------------------------------------------------------------------------------------------------------------------")
print("El apellido paterno es: ", apelli_paterno)
print("El apellido materno es: ", apelli_materno)
print("El primer nombre es: ", nombre)
print("El segundo nombre es: ", nombre2)
print(" ")

# Mostrar la lista original
print("Lista original:", con)

# Convertir los elementos de la lista a mayúsculas y mostrarla
con_mayus = [element.upper() for element in con]
print("Lista en mayúsculas:", con_mayus)
print("------------------------------------------------------------------------------------------------------------------------------------------------")

![image](https://github.com/user-attachments/assets/5974cf51-1bef-4bd4-b4e9-d9c166b64325)
![image](https://github.com/user-attachments/assets/68c142ae-0786-41cc-957c-70b3ab4c49df)
