# Exercicios--de-Python-Let-s-code
Resolução exercícios bootcamp let´s code 


1. Faça um programa que peça um valor monetário e diminua-o em 15%. Seu
programa deve imprimir a mensagem “O novo valor é [valor]”.

Resolução:

Valor_monetario = input('digiter o valor: ')
Valor_monetario = float(Valor_monetario)

Novo_Valor = Valor_monetario*15/100
Novo_Valor = Valor_monetario - Novo_Valor

print('O novo valor é:',Novo_Valor)
