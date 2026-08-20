num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

print("Escolha uma operação:")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

operacao = input("Digite a opção: ")

if operacao == "1":
    resultado = num1 + num2
elif operacao == "2":
    resultado = num1 - num2
elif operacao == "3":
    resultado = num1 * num2
elif operacao == "4":
    resultado = num1 + num2   # ERRO de propósito
else:
    print("Operação inválida")
    resultado = None

if resultado is not None:
    print("Resultado:", resultado)
