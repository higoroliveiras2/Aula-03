# Aula-03
Ficha de cadastro
nome = input("Qual é o seu nome? ")
idade = int(input("Qual é a sua idade? "))
altura = float(input("Qual é a sua altura (em metros, ex: 1.65)? "))
cidade = input("Qual é a cidade onde você nasceu? ")
numero_favorito = int(input("Qual é o seu número favorito? "))
nome_pet = input("Qual o nome do seu pet? ")


altura_cm = altura * 100
dias_vividos = idade * 365  # Aproximadamente
semanas_vividas = idade * 52  # Aproximadamente
letras_pet = len(nome_pet)
curiosidade_matematica = idade * numero_favorito


print()
print("Ficha Curiosa de", nome)
print("Olá, que bom te ver aqui", nome + "!")
print(f"Você já viveu aproximadamente {dias_vividos} dias.")
print(f"E cerca de {semanas_vividas} semanas.")
print(f"Sua altura em centímetros é: {altura_cm:.2f} cm.")
print(f"O nome do seu pet tem {letras_pet} letras.")
print(f"Uma curiosidade matemática: sua idade multiplicada pelo seu número favorito é {curiosidade_matematica}.")
print(f"Você nasceu em {cidade}.")
