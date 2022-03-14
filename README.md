# cadastramento


print("Boa tarde, bem vindo a nossa plataforma!")
print("para começarmos precisamos saber se voçê é pessoa fisica ou juridica")
print(" digite abaixo 1 para juridica e 2 para fisica")

pessoa= int(input(" Juridica\n Fisica\n -:"))

while pessoa < 1 or pessoa >2:
        print("Algo deu errado digite 1 para pessoa juridica ou 2 para pessoa fisica ")
        pessoa= int(input("JUridica\n Fisica\n -:")
    
    if pessoa ==1:
        nomef= input("Insira seu nome fantasia\n-:")
        razao= input("Razão social\n-:")
        cnpj= input("Digite seu CNPJ\n-:")
        print("Cadastro feito com sucesso aqui estão seus dados cadastrados")
        print("Nome fantasia\n", nomef, "\n Razão social\n",razao, "\nCNPJ\n",cnpj)
        
    elif pessoa == 2:
        nome = input("Digite seu nome completo\n -:")
        cpf= input("Digite seu CPF\n-:")
        print("Cadastro feito com sucesso aqui estão seus dados cadastrados")
        print("Nome\n", nome, "\nCPF\n" , cpf)
