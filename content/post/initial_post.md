---
title: "Conversor de Moedas em Python"
date: 2022-01-16T01:51:44-03:00
draft: false
---

Crie um programa que leia quanto dinheiro uma pessoa tem na carteira e mostre quantos Dólares ela pode comprar. Considere US$1,00 = R$3,37

'''

real = float(input('Quanto  de dinheiro você tem na carteira? R$'))
dolar = real / 5.63

#Usamos o {} com o .format para que seja colocado as variaveis no lugar {}.
#Colocamos o {:.2f} para formatar ainda mais, sendo que desse modo o nosso valor exibito terá apenas 2 casas decimais flutuantes.

print('Com R${:.2f} você pode comprar US${:.2f}'.format(real, dolar))

'''