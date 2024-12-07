# kodland
este es mi primer repositorio
# Sorprende a tus compañeros
import random
print("estos son mis datos:")
while True:
    datos = ["soy imperativo", "me gustan los dulces", "me encanta roblox", "juego blox fruits", "me gusta jugar con mis amigos :)", "amo explorar", "me gusta esconderme,ummm... donde estare ahora?", "mi mascota es la mejor", "el alimentador de animeles es un proyecto del que me siento orgulloso"]
    print(random.choice(datos))
    opinion = input("quieres parar?")
    if opinion == "no":
        print("==================================================")
    elif opinion == "si":
        break
