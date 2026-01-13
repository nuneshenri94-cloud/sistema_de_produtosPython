print("PEDRA, PAPEL OU TESOURA !")
import random
computador = random.choice(["Pedra", "Papel", "Tesoura"])
pessoa = input("Você quer pedra, papel ou tesoura? ")

print("Você escolheu {}".format(pessoa))
print("O computador escolheu {}".format(computador))

if pessoa == computador:
    print("Deu empate!")

elif (pessoa == "Papel" and computador == "Tesoura") or (pessoa == "Pedra" and computador == "Papel") or (pessoa == "Tesoura" and computador == "Pedra"):
   print("Você perdeu!")

else:
  print("Você ganhou!")
