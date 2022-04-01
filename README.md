# Contador-de-nome-completo-de-usuário
Este contador tem o objetivo de receber o nome completo do usuário, contar a quantidade de palavras presentes nesse nome e apontar a ordem em que cada nome se encontra. Esse código é feito em Python.

nome = input('\n\nDigite aqui o seu nome completo: ').title()
nomeRecortado = nome.split()
quantDePalavras = len(nomeRecortado)
print(f'\nSeu nome é formado por {quantDePalavras} palavras:\n')


contador = 0
ordemDoNome = ['Primeiro: ','Segundo: ','Terceiro: ','Quarto: ','Quinto: ','Sexto: ','Sétimo: ','Oitavo: ','Nono: ','Décimo: ']
              
for i in range(0, quantDePalavras):
               print(ordemDoNome[contador], nomeRecortado[contador])
               contcarac = len(nomeRecortado[contador])
               print('Quantidade de letras nessa palavra: ', contcarac,'\n')
               contador = contador + 1
    
