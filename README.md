# Exercicio082.py

pares = list()
impares = list()
num = list()
while True:
    num.append(int(input('Digite um numero?')))
    resp = str(input('Quer continuar? [S/N]'))
    if resp in 'Nn':
        break
for i,v in enumerate(num):
    if v % 2 == 0:
        pares.append(v)
    elif v % 2 == 1:
        impares.append(v)
print(f'A lista completa{num}')
print(f'A lista de pares:{pares}')
print(f'A lista de impares{impares}')
