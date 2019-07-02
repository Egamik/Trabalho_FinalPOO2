# Trabalho_FinalPOO2

business management
	
	1- Aba planejamento de custos
		- Escolhe período do orçamento(Meses)
			- Adiciona o quanto vai sair do caixa no periodo
				- Pode ter file q salva como extrato
		- Dislpay da taxa de fluxo de caixa(Pode ver dos meses anteriores *FILE*) 
		- Pode inserir emprestimos feitos(precisa dos juros)
		- Pode inserir custos mensais
		- Pode inserir gastos exepcionais
		
	2- Aba Caixa
		- Insere valor de entrada e descrição do item vendido
		- Requer login de funcionario 

	3- Aba funcionarioss
		- Cadastra funcionario novo
			- Requer pw
		- Mantem os dados dos funcionarios
			- Mostra cargo, salário e setor de responsabilidade
	4- Aba Catalogo
		- Mostra produtos e seus precos
		- Possiblita a edição dos itens a venda e seus precos
		- Conversa com classe estoque para checar disponibilidade dos itens

	5- Classe Estoque
		- Guarda categorias de produtos (Array)
        	- Salva em file uma Hashtable com todas as categorias 
	
	6- Classe Produtos
		- Nome, Marca, Preco, setor
		
	7- Classe Funcionario
		- Nome, cargo, salario
