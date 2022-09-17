# Suspeita-Contágio-Covid-19
#Programa que realiza triagem em casos de possível contágio por Covid-19, determinando atendimento prioritário e sala específica para idosos com suspeita de contágio.

nome=input("Digite o nome: ")
idade=int(input("Digite a idade: "))
doenca_infectocontagiosa=input("Suspeita de contágio por Covid-19?").upper()
if idade >= 65:
    print("Paciente COM prioridade")
    if doenca_infectocontagiosa=="SIM":
        print("Encaminhe o paciente para sala AMARELA")
    elif doenca_infectocontagiosa=="NAO":
        print("Encaminhe o paciente para sala BRANCA")
    else:
        print("Responda a suspeita decontágio por Covid-19 com SIM ou NAO")
else:
    print("Paciente SEM prioridade")
    if doenca_infectocontagiosa=="SIM":
        print("Encaminhe o paciente para sala AMARELA")
    elif doenca_infectocontagiosa=="NAO":
        print("Encaminhe o paciente para sala BRANCA")
    else:
        print("Responda a suspeita de contágio por Covid-19 com SIM ou NAO")
