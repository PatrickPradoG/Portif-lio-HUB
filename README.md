# Portifolio-HUB
Alguns códicos feitos em python da aula de Lógica de programação
----------------------------------------
base=float(input("Digite a base:"))
altura=float(input("Digite a altura:"))
area=base*altura/2
print("Área:",area)
print(f"Área:{area:.3f}")
----------------------------------------
ct=0
soma=0
print("digite [-1] para sair da repetição")
while True:
    nota=float(input("nota:"))
    if nota== -1:
        break
    ct=ct+1
    soma=soma+nota
media=soma/ct
print("Quantidade de alunos:",ct)
print("media da turma",media)
----------------------------------------
