# Calculadora Interativa(+, -, *, /)

user_name = input("Digite seu nome: ")

print(f'Olá, {user_name}! Escolha seus valores e escolha sua operção desejada.')

# As entradas de num1 e num2 devem vir antes da lógica de operação
num1 = int(input("Digite seu primeiro número: "))
num2 = int(input("Digite seu segundo número: "))

operador = input('Escolha entre: Soma - 1 / Subtração - 2 / Divisão - 3 / Multiplicação - 4: ')

# Substituindo o loop e o 'return' por uma estrutura if/elif/else e 'print'
if operador == '1': # Comparar string com string
  print(f"Resultado da Soma: {num1 + num2}")
elif operador == '2':
  print(f"Resultado da Subtração: {num1 - num2}")
elif operador == '3':
  if num2 != 0:
    print(f"Resultado da Divisão: {num1 / num2}")
  else:
    print("Erro: Não é possível dividir por zero!")
elif operador == '4':
  print(f"Resultado da Multiplicação: {num1 * num2}")
else:
  print("Operação inválida. Por favor, escolha um número de 1 a 4.")
