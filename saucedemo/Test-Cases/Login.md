-\\-
	Test Cases Referente à Função de Login - PT-BR
-\\-
	
	Critérios 		- Capos de Email e Senha são Obrigatórios
					- Usuário Só Consegue Logar Com Conta Existente					
	URL: https://sauce-demo.myshopify.com/account/login
	Pré-condições   - Usuário Tenha Uma conta Cadastrada
					- Usuário Não Está Logado
	Dados de teste 	- Email: jl.genericutesting@gmail.com
					- Password: test123
			
		- Início -
		
	TC-001 - Logar Com Sucesso
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Preencher campo 'Email Address' Com dados válidos
		3. Preencher campo 'Password' com dados válidos
		4. Clicar no botão 'SIGN IN' 
		
		Resultado esperado - 
			Usuário ser redirecionado para a página 'My Account' e Logar com sucesso
		
		Status: Aprovado 🟩
		
	TC-002 - Logar com Email Inexistente
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Preencher campo 'Email Address' Com dados inexistentes (Por Exemplo: jl.noexistingemail@gmail.com)
		3. Preencher campo 'Password' com dados válidos
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email e/ou Senha estão errados (Incorrect email or password.)
			
		Status: Aprovado 🟩
			 
	TC-003 - Logar com Email Existente e Senha incorreta 
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Preencher campo 'Email Address' Com dados válidos
		3. Preencher campo 'Password' com dados divergentes da senha cadastrada para o Email
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email e/ou Senha estão errados (Incorrect email or password.)
		
		Status: Aprovado 🟩
			
	TC-004 - Logar com Campo 'Email Address' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Manter campo 'Email Address' Vazio
		3. Preencher campo 'Password' com dados válidos
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email e/ou Senha estão errados (Incorrect email or password.)
		
		Status: Aprovado 🟩
			
	TC-005 - Logar com Campo 'Password' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Preencher campo 'Email Address' com dados válidos
		3. Manter campo 'Password' vazio
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email e/ou Senha estão errados (Incorrect email or password.)
		
		Status: Aprovado 🟩
		
	TC-006 - Logar com Campos 'Email Address' e 'Password' Vazios
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Manter campo 'Email Address' vazio
		3. Manter campo 'Password' vazio
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email e/ou Senha estão errados (Incorrect email or password.)
		
		Status: Aprovado 🟩

	TC-007 - Logar com campo 'Email Address' em Formato Inválido
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/account/login
		2. Preencher campo 'Email Address' com dados em formato incorreto (por exemplo: invalidemail.com)
		3. Preencher campo 'Password' com dados válidos
		4. Clicar no botão 'SIGN IN'
		
		Resultado esperado - 
			Exibição de mensagem de erro informando que o Email deve incluir um "@"
		
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
