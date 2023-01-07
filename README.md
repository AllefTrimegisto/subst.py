# subst.py

nome = "Allef Alexandre"
print(nome) #Imprimindo a String
print(type(nome)) #Monstrando o tipo de de classe
print(len(nome)) #Tamanho da String
print(nome + " Alexandre") #Concatenação1
print("Allef", "Alexandre") #Concatenação2
substituicao = nome.replace("Alexandre", "Domingos")
print(substituicao)
print(nome.startswith("Allef")) #Verificando se a string começa com "Edson"
print(nome.endswith("Alexandre")) #Verificando se a string começa com "Edson"
print(nome.count("e")) #Verificando quantas letras e (menusculas tem na string)
maiusculas = nome.upper() #colocando todas as letras maiusculas
print(maiusculas)
menusculas = nome.lower() #colocando todas as letras menusculas
print(menusculas)
