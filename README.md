# Evaluaci-n-4
ingrese_usuario = str(input ("Ingrese su usuario: "))
numero_de_usuarios = 3
nuevo_usuario = 0
usuarios_registrados = ["Fernando", "Eduardo", "Daniela"]
eliminar_usuario = str(input("Nombre del usuario a eliminar: ")) 


print ("---------------------- \n Menu principal \n 1. Ingresar usuario \n 2. Buscar usuario \n 3. Eliminar usuario \n 4. Terminar Programa \n --------------------------------------")



lista_usuarios = {
    "usuario 1: " : "Fernando",
    "Edad" : 25,
    "Contraseña :" : 1234,
}
{
    "usuario 2: " : "Eduardo",
    "Edad" : 49,
    "Contraseña :" : 4321,
}
{
    "usuario 3: " : "Daniela",
    "Edad" : 28,
    "Contraseña :" : 2222,
}


while True:
    try:
        if ingrese_usuario not in lista_usuarios.values():
            raise ValueError("Usuario no encontrado.")
        break
    finally:

if ingrese_usuario == lista_usuarios["usuario 1: "]:
    print("Usuario correcto")
    ingreso_contraseña = input("Ingrese su contraseña: ")
    
    if ingreso_contraseña == int(lista_usuarios["Contraseña :"]):
        print("Su contraseña es correcta")
        print("Bienvenido"), lista_usuarios[0]["usuario 1: "]
    else:
        print("Contraseña incorrecta, trate con otra")
    

for i in range(numero_de_usuarios):
    nuevo_usuario += 1
    print(f"Usuario {nuevo_usuario} ingresado correctamente.")
    nombre = str (input("Ingrese el nombre del nuevo usuario: "))
    edad = int(input("Ingrese la edad del nuevo usuario: "))
    contraseña = int (input("Ingrese la contraseña del nuevo usuario: "))
    
    lista_usuarios[f"usuario {nuevo_usuario}: "] = nombre
    lista_usuarios["Edad"] = edad
    lista_usuarios["Contraseña :"] = contraseña

    def mostrar_usuarios():
        for key, value in lista_usuarios.items():
            print(f"{key} {value}")
        mostrar_usuarios()
        print("Error al ingresar el usuario. Intente nuevamente.")
        continue

if ingrese_usuario == lista_usuarios["usuario 2: "]:
    print("Usuario correcto")
    ingreso_contraseña = input("Ingrese su contraseña: ")
    
    if ingreso_contraseña == int(lista_usuarios["Contraseña :"]):
        print("Su contraseña es correcta")
        print("Bienvenido"), lista_usuarios[1]["usuario 2: "]
    else:
        print("Contraseña incorrecta")
for i in range(numero_de_usuarios):
    nuevo_usuario += 1
    print(f"Usuario {nuevo_usuario} ingresado correctamente.")
    nombre = str (input("Ingrese el nombre del nuevo usuario: "))
    edad = int(input("Ingrese la edad del nuevo usuario: "))
    contraseña = int (input("Ingrese la contraseña del nuevo usuario: "))
    
    lista_usuarios[f"usuario {nuevo_usuario}: "] = nombre
    lista_usuarios["Edad"] = edad
    lista_usuarios["Contraseña :"] = contraseña

    def mostrar_usuarios():
        for key, value in lista_usuarios.items():
            print(f"{key} {value}")
        mostrar_usuarios()
        print("Error al ingresar el usuario. Intente nuevamente.")
        continue

if ingrese_usuario == lista_usuarios["usuario 3: "]:
    print("Usuario correcto")
    ingreso_contraseña = input("Ingrese su contraseña: ")
    
    if ingreso_contraseña == int(lista_usuarios["Contraseña: "]):
        print("Su contraseña es correcta")
        print("Bienvenido: "), lista_usuarios[2]["usuario 3: "]
    else:
        print("Contraseña incorrecta")  
for i in range(numero_de_usuarios):
    nuevo_usuario += 1
    print(f"Usuario {nuevo_usuario} ingresado correctamente.")
    nombre = str (input("Ingrese el nombre del nuevo usuario: "))
    edad = int(input("Ingrese la edad del nuevo usuario: "))
    contraseña = int (input("Ingrese la contraseña del nuevo usuario: "))
    
    lista_usuarios[f"usuario {nuevo_usuario}: "] = nombre
    lista_usuarios["Edad"] = edad
    lista_usuarios["Contraseña :"] = contraseña

    def mostrar_usuarios():
        for key, value in lista_usuarios.items():
            print(f"{key} {value}")
        mostrar_usuarios()
        print("Error al ingresar el usuario. Intente nuevamente.")
        continue

else: print ("Nada")
