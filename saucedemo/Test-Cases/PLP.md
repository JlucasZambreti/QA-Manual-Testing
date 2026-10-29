-\\-
	Test Cases referente à função de Listagem de Produtos - PT-BR
-\\-
	
	Critérios 		- Todos os produtos devem ser listados corretamente
					- Valores exibidos devem ser identicos ao PDP
					- Nomes dos produtos exibidos devem ser identicos ao PDP

	URL: https://sauce-demo.myshopify.com/collections/all
	Pré-condições   - Usuário tenha conta registrada
					- Usuário está logado
	Dados de teste 	- Email: jl.genericutesting@gmail.com
					- Password: test123
			
		- Início -
		
	TC-001 - Listagem de Produtos Com Estoque
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Navegar pela seção de listagem dos produtos
		
		Resultado esperado -
			Todos os produtos sejam carregados corretamente, contendo Imagem, Nome e Preço
		
		Status: Aprovado
			
	TC-002 - Listagem de Produtos com Falta de Estoque
	
		Prioridade: ALTA
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Navegar pela seção de listagem dos produtos
		
		Resultado esperado -
			Todos os produtos sejam carregados corretamente, contendo Imagem, Nome, Preço E exibir faixa informando a falta de estoque do produto
		Status: Aprovado
			
	TC-003 - Acessar Um Produto Listado Com Estoque
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de listagem de produtos
		3. Clicar no produto listado com estoque "Black Heels"
		
		Resultado esperado -
			Ser redirecionado para página de detalhes do produto "Black heels" Com sucesso
		
		Status: Aprovado
			
	TC-004 - Acessar Um Produto Listado Sem Estoque
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/collections/all
		2. Descer a página até a seção de listagem de produtos
		3. Clicar no produto listado sem estoque "Brown Shades"
		
		Resultado esperado - 
			Ser redirecionado para página de detalhes do produto "Brown Shades" Com sucesso
		
		Status: Aprovado
			

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
