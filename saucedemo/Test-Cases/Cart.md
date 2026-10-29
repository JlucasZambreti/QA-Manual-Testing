-\\-
	Test Cases Referente à Página do Carrinho De Compras - PT-BR
-\\-
	
	Critérios 		- Produto deve ser detalhado corretamente com preço, nome e imagem Identicos ao usado no PLP/PDP
	URL:https://sauce-demo.myshopify.com/#
	Pré-condições   - Usuário Tenha Conta Cadastrada
					- Usuário Esteja Logado
					- Usuário Tenha Ao Menos 1 Produto Adicionado ao Carrinho
					- Produto Adicionado Não Pode ser "Noir jacket"
	Dados de teste 	- Email: jl.genericutesting@gmail.com
					- Password: test123
		- Início -
		
	TC-001 - Finalizar Carrinho de Compras e Iniciar Processo de Check Out
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/#
		2. Clicar no Botão "My Cart (1)" Localizado no Menu superior
		3. Clicar no Botão "CHECK OUT" 
		
		Resultado esperado - 
			Usuário ser redirecionado para a página de Check Out com sucesso, produtos, valores e quantias exibidas serem identicas aos dados do carrinho de compras
			
		
		Status: Aprovado 🟩
		
	TC-002 - Iniciar Processo de Check Out sem produtos no carrinho
	
		Prioridade: Alta 
		
		Pré-Condições: Usuário não deverá ter produtos adicionado ao carrinho
		Passos - 
		1. Acessar https://sauce-demo.myshopify.scom/#
		2. Clicar no Botão "My Cart (0)" Localizado no Menu superior
		
		Resultado esperado - 
			Mensagem "Your cart is empty." ser exibida e botão de "Check Out" estar indisponível
		
		Status: Aprovado 🟩
			
	TC-003 - Remover Produto do Carrinho
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/#
		2. Clicar no Botão "My Cart (1)" Localizado no Menu superior
		3. Clicar no botão "Remove"
		
		Resultado esperado - 
			Produto ser removido do carrinho com sucesso, mensagem de "Your cart is Empty." ser exibida e botão de "Chek Out" estar indisponível
		
		Status: Aprovado 🟩
				
	TC-004 - Remover Produto do Carrinho com 2 Itens Diferentes Adicionados
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/# 
		2. Descer a Página para a seção de Produtos
		3. Clickar no card do produto "Noir jacket"
		4. Clicar no botão "ADD TO CART"
		5. Clicar no botão "My Cart (2)" Localizado no Menu superior da página
		6. Clicar no botão "Remove" referente ao produto "Noir Jacket"
		
		Resultado esperado - 
			Carrinho atualizar e remover com sucesso o produto "Noir Jacket", Botão de "Check Out" ainda estar ativo e produto adicionado previamente ainda estar visivel
		
		Status: Aprovado 🟩

	TC-005 - Alterar Quantia do Produto
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/#
		2. Clicar no Botão "My Cart (1)" Localizado no Menu superior
		3. Alterar Text Box de Unidade, de "1" para "10"
		4. Pressionar "Enter"
		
		Resultado esperado - 
			Produto ser alterado para 10 unidades e valor total ser alterado para a nova quantia
			
		Status: Aprovado 🟩
		
	TC-006 - Alterar Quantia do Produto Para "0"
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/#
		2. Clicar no Botão "My Cart (1)" Localizado no Menu superior
		3. Alterar Text Box de Unidade, de "1" para "0"
		4. Pressionar "Enter"
		
		Resultado esperado - 
			Produto ser removido do carrinho, mensagem de "Your cart is Empty." ser exibida e botão de "Chek Out" estar indisponível
			
		Status: Aprovado 🟩

		- Fim -
-\\-
	TITLE - EN-US
-\\-
		- Start -
	Criteria		- 
	URL: 
	Preconditions   - 
	Test Data 		- 
	
		- Start -
		
	TC-000 - 
	
		priority: 
		
		Steps - 
		1. 
		2. 
		3. 
		4. 
		5. 
		6. 
		7. 
		
		Expected Result - 
			
		
		Status: 
		- End - 
		
-\\-
