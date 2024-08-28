# EX-AULAS
EXERCIOS DAS AULAS 
# 1 Imprima uma mensagem de boas-vindas na tela.
# lista = ['boas vindas']
# print (lista)

# 2 Declare uma variável booleana verdadeiro com o valor True e imprima seu tipo
# var = True
# print(var)

# 3 Imprima o resultado da multiplicação de dois números decimais de sua escolha
# n1 = float(input('DIGITE UM NUMERO DECIMAL'))
# n2 = float(input('DIGITE OUTRO NUMERO DECIMAL'))
# mult = n1*n2
# print (mult)

# 4 Imprima o resultado da divisão de dois números inteiros de sua escolha.
# n1 = int(input('DIGITE UM NUMERO INTEIRO '))
# n2 = float(input('DIGITE OUTRO NUMERO INTEIRO '))
# div = n1/n2
# print (div)

# 5 Imprima o resultado da subtração de dois números inteiros de sua escolha
# n1 = int(input('DIGITE UM NUMERO INTEIRO '))
# n2 = float(input('DIGITE OUTRO NUMERO INTEIRO '))
# subtração = n1-n2
# print (subtração)

# # 6 Imprima o resultado da divisão inteira de dois números inteiros de sua escolha.
# n1 = int(input('DIGITE UM NUMERO INTEIRO '))
# n2 = float(input('DIGITE OUTRO NUMERO INTEIRO '))
# div = n1//n2
# print (div)

# 7 Imprima o resultado da multiplicação de 4 números decimais de sua escolha
# n1 = float(input('DIGITE UM NUMERO DECIMAL '))
# n2 = float(input('DIGITE OUTRO NUMERO DECIMAL '))
# n3 = float(input('DIGITE OUTRO NUMERO DECIMAL '))
# n4 = float(input('DIGITE OUTRO NUMERO DECIMAL '))
# mult = n1*n2*n3*n4
# print (mult)

# 8 Declare uma variável numero e atribua um número inteiro. Em seguida, imprima o dobro desse número
# num = int(input('DIGITE UM NUMERO INTEIRO '))
# dobro = num * 2
# print(dobro)


# 9 Crie uma calculadora de soma com as ferramentas que vc já 
# conhece(Use apenas input, print e variavel)
# numero1 = int(input('DIGITE UM NUMERO'))
# numero2 = int(input('DIGITE OUTRO NUMERO'))
# soma = numero1 + numero2
# print ('ESTE É O SEU RESULTADO', soma)

# 10 Crie um sistema de cadastro com as estruturas que vc já conhece(Use apenas input, print e variavel)
# info1 = str(input('DIGITE SEU NOME '))
# info2 = int(input('DIGITE SEU CPF '))
# info3 = str(input('DIGITE SEU ENDEREÇO '))
# fim = ('CADASTRO FINALIZADO')
# print (fim)

nome = input('digite o nome do aluno')
print('Notas escola x')
nota_mat = float(input('DIGITE A NOTA'))
nota_port = float(input('DIGITE A NOTA'))
nota_ing = float(input('DIGITE A NOTA'))
nota_geo = float(input('DIGITE A NOTA'))

soma = nota_mat + nota_port + nota_ing + nota_geo
media= soma / 4
#concatenar == juntar
print ('media do aluno:', nome,)
print ('media do aluno', media)
situacao = media >= 7
print ('situação do aluno: APROVADO', situacao)
