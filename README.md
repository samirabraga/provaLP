# Inicialize uma lista vazia para armazenar os números pares
numeros_pares = []

# Use um loop para pedir ao usuário 5 números inteiros
for i in range(5):
    numero = int(input("Digite um número inteiro entre 0 e 10: "))
    
    # Verifique se o número é par
    if numero % 2 == 0:
        numeros_pares.append(numero)

# Imprima os números pares
print("Números pares digitados: ", numeros_pares)
