# Contador-de-nome-completo-de-usuário
Este contador tem o objetivo de receber o nome completo do usuário, contar a quantidade de palavras presentes nesse nome e apontar a ordem em que cada nome se encontra. Esse código é feito em python

nome = input('Digite aqui o seu nome completo: ')
nomeRecortado = nome.split()
quantDePalavras = len(nomeRecortado)
print(f'Seu nome é formado por {quantDePalavras} palavras')

contador = 0
ordemDoNome = ['Primeiro: ','Segundo:','Terceiro: ','Quarto: ','Quinto: ','Sexto: ','Sétimo: ','Oitavo: ','Nono: ','Décimo: ']
              
for i in range(0, quantDePalavras):
               print(ordemDoNome[contador], nomeRecortado[contador])
               contador = contador + 1
