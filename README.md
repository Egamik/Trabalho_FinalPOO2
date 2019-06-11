# Trabalho_FinalPOO2

business planner
	
	1- Aba planejamento de custos
		- Escolhe período do orçamento(Meses)
			- Adiciona o quanto vai sair do caixa no periodo
				- Pode ter file q salva como extrato
		- Dislpay da taxa de fluxo de caixa(Pode ver dos meses anteriores *FILE*) 
		- Pode inserir emprestimos feitos(precisa dos juros)
		- Pode inserir custos de aluguel do estoque
		- 
	2- Aba Caixa
		- Insere valor de entrada e descrição do item vendido
		- Calcula fluxo de caixa baseado no fluxo de estoque 

	3- Aba funcionarioss
		- Requer senha de admin para acessar
		- Cadastra funcionario novo
		- Matem os dados dos funcionarios
			- Mostra cargo, salário e setor de responsabilidade
	4- Aba Catalogo
		- Mostra produtos e seus precos
		- Possiblita a edição dos itens a venda e seus precos
		- Conversa com classe estoque para checar disponibilidade dos itens

	5- Classe Estoque
		- Guarda conjunto de produtos
			- Soh precisa do numero de produtos e nome
     		- Fornece fluxo de produtos
        	- Salva em file o historico com o nome do produto o numero que entrou ou saiu e o valor 
	
	6- Classe Produtos
		- Nome, Marca, Preco, setor
