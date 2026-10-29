-\\-
	Test Cases Referente à Página de Detalhes do Produto - PT-BR
-\\-
	
	Critérios 		- Produto deve ser detalhado corretamente com preço, nome e imagem Identicos ao usado no PLP
					- Produtos fora de estoque tem páginas de detalhe do produto mas não podem ser adicionados ao carrinho

	URL: https://sauce-demo.myshopify.com/collections/all
	Pré-condições   - Usuário Tem Conta Cadastrada
					- Usuário Está logado
	Dados de teste 	- Email: jl.genericutesting@gmail.com
					- Password: test123 
			
		- Início -
		
	TC-001 - Detalhes do Produto Com Estoque é Exibido Corretamente
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de Listagem de produtos
		3. Clicar em um produto listado com estoque (Por exemplo: Black Heels)
		
		Resultado esperado - 
			Ser redirecionado para a página de detalhes do produto clicado, exibindo nome, preço e imagem identicos à página de listagem
		
		Status: Falhou
		
		Resultado obtido - 🟥
			URL do Produto clicado "Black heels" é referente ao "flower print jeans" Porém nome, preço e imagem estão exibidas corretamente
		
	TC-002 - Detalhes do Produto Sem Estoque é Exibido Corretamente
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de Listagem de produtos
		3. Clicar em um produto listado sem estoque (Por exemplo: Brown Shades)
		
		Resultado esperado - 
			Ser redirecionado para a página de detalhes do produto sem estoque clicado, exibindo nome, preço e imagem identos à página de listagem
		
		Status: Aprovado 🟩
		
	TC-003 - Adicionar Produto Com Estoque Ao Carrinho com Sucesso
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de Listagem de produtos
		3. Clicar em um produto listado com estoque (Por exemplo: Bronze Sandals)
		4. Clicar no botão "ADD TO CART"
		
		Resultado esperado - 
			Produto ser Adicionado ao carrinho e atualizar a quatia de produtos ao carrinho no menu superior da página
		
		Status: Aprovado 🟩
			
	TC-004 - Adicionar Produto Sem Estoque Ao Carrinho
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de Listagem de produtos
		3. Clicar em um produto listado sem estoque (Por exemplo: Brown Shades)
		4. Clicar no botão "ADD TO CART"
		
		Resultado esperado - 
			Botão "ADD TO CART" estar com o texto trocado para "SOLD OUT" e estar inclicável
		
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
