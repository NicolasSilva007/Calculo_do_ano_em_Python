# Calculo_do_ano_em_Python

nome = input("Digite o nome: ")
idade = int(input("Digite idade:"))
ano = int(input("Ano de nascimento: "))
saldo = float(input("Digite seu saldo: "))
percen = int(input("Digite o percentual: "))

print (nome,"seu saldo é: ",saldo)
print ("Seu saldo com mais",percen,"%:",(saldo * percen)/100+saldo)

print ("--------------------------------------------------------------------")
print (f"Você {nome} que nasceu em {ano} tera um saldo de {percen}%, que sera de R$ {(saldo*percen)/100+saldo}")
print ("--------------------------------------------------------------------")

