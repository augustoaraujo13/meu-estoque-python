print("Vamos cadastrar um produto")

print("-------------------")
nome_do_produto = str(input("Digite o nome do produto: "))
categoria_do_produto = str(input("Digite a categoria: "))
valor_do_produto = float(input("Digite o valor: "))
quantidade_do_produto = int(input("Digite a quantidade: "))
print("-------------------")


def estoque():
    print("-------------------")
    print(f"Nome do produto: {nome_do_produto}")
    print(f"Categoria do produto: {categoria_do_produto}")
    print(f"Valor do produto: {valor_do_produto:.2f}")
    print(f"Valor total do estoque: {valor_do_produto * float(quantidade_do_produto)}")
    print("-------------------")


print(estoque())