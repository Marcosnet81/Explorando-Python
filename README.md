# Explorando-Python
Esse Codigo, É Mais uma Diversão pra mim, pois tento aperfeiçoar cada dia as opções do Puthon, uma linguagem que gosto muito.
from random import randint
computador = randint(0, 10)
print('Sou o Computador... Acabei de pensar em um número entre 0 e 10 ')
acertou = False
palpite = 0
while not acertou:
    jogador = int(input('Qual o seu Palpite: '))
    palpite += 1
    if jogador == computador:
        acertou = True
        print('Parabéns você acertou !!!')
    else:
        if jogador < computador:
            print('Mais... tente outra Vez.')
        elif jogador > computador:
            print(('Menos... tente mais uma vez. '))
print(f'Acertou com {palpite} tentativas. Parabéns')
