# tanyac05
Config files for my GitHub profile.
def solicitar_nombre():
    nombre = input("Por favor, ingresa tu nombre: ").strip()
    while not nombre:
        print("No has ingresado un nombre válido. Intenta nuevamente.")
        nombre = input("Por favor, ingresa tu nombre: ").strip()
    return nombre

def saludar(nombre):
    print(f"Hola, {nombre}! ¡Bienvenido a Programación!")

def main():
    nombre = solicitar_nombre()
    saludar(nombre)

if __name__ == "__main__":
    main()
