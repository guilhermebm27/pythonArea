# pythonArea
Python Calcular Área
# Faça um programa que leia a largura e a altura de uma
# parede em metros, calcule a sua área e a quantidade
# necessária para pintá-la, sabendo que cada litro de tinta
# pinta uma área de 2m².
print('***** Informar entrada de dados, largura e altura *****')
larg = float(input('Largura da parede: '))
alt = float (input('Autura da  parede: '))
area = larg * alt
print ('Sua parede tem a dimensão de {} x {} e sua área de {}m².'.format(larg,alt,area))
tinta = area /2
print ('para pintar essa parede, você precisará de {} L de tinta.'.format(tinta
