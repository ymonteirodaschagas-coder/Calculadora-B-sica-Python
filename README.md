# Calculadora-B-sica-Python
print('Calculadora Básica')
print('escolha uma opção')
print('[1}Soma')
print('[2]Subtração')
print('[3]Multiplicação')
print('[4]Divisão')
opcao = int(input())

numero1 = int(input('digite o primeiro número:'))
numero2 = int(input('digite o segundo número:'))

 if opcao == 1:
  print(f'Resultado da soma é: {numero1+numero2}')
 elif opcao == 2:
  print(f'Resuldado da subtração é: {numero1-numero2}')
 elif opcao == 3:
  print(f'Resuldado da multiplicação é: {numero1*numero2}')
 elif opcao == 4:
  print(f'Resuldado da divisão é: {numero1/numero2}')
