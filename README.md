# jogo
 bom
from random import randint
computador = randint(0, 7)
print('°-°' * 17) #fazer brincadeiras
print('Vou pensar em um número de 0 a 7.Tente adivinhar...')
print('°-°' * 17)
jogador = int(input('Em que número eu pensei ? ')) #jogador tenta adivinha
if jogador == computador:   
    print('CONGRATULATIONS VOÇÊ VENCEU!!!!!')
else:        
    print('GANHEI EU PENSEI NO NUMERO {} E NÃO NO {}!'.format(computador, jogador))
