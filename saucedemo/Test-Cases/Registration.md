-\\-
	Test cases referente à função de registro - PT-BR
-\\-
	
	Critérios 		- Usuário deve conseguir criar uma conta utilizando dados válidos.
					- Campos obrigatórios não devem aceitar valores vazios.
					- O campo de Email deve aceitar apenas endereços em formato válido.
	URL: https://sauce-demo.myshopify.com/
	Pré-condições - N/A
	Dados de teste 	- Email: jl.genericutesting@gmail.com
					- Password: test123
					- First name: João
					- Last Name: Test
					
		- Início -
		
	TC-001 - Registrar com Sucesso
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Preencher campo 'First Name' com dados válidos
		4. Preencher campo 'Last Name' com dados válidos
		5. Preencher campo 'Email Address' com dados válidos
		6. Preencher campo 'Password' com dados válidos
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Usuário ser cadastrado com sucesso e redirecionado para a Home com sua conta Logada
		
		Status: Aprovado
		
		
	TC-002 - Registrar com Campo 'First Name' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Manter campo 'First Name' vazio
		4. Preencher campo 'Last Name' com dados válidos
		5. Preencher campo 'Email Address' com dados válidos
		6. Preencher campo 'Password' com dados válidos
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro 'First name can't be blank.'
		
		Status: Aprovado
		
	TC-003 - Registrar com Campo 'Last Name' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Preencher campo 'First Name' com dados válidos
		4. Manter campo 'Last Name' vazio
		5. Preencher campo 'Email Address' com dados válidos
		6. Preencher campo 'Password' com dados válidos
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro 'Last name can't be blank.'
		
		Status: Aprovado
		
	TC-004 - Registrar com Campo 'Email Address' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Preencher campo 'First Name' com dados válidos
		4. Preencher campo 'Last Name' com dados válidos
		5. Manter campo 'Email Address' vazio
		6. Preencher campo 'Password' com dados válidos
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro 'Email can't be blank.'
		
		Status: Aprovado
		
	TC-005 - Registrar com Campo 'Password' Vazio
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Preencher campo 'First Name' com dados válidos
		4. Preencher campo 'Last Name' com dados válidos
		5. Preencher campo 'Email Address' com dados válidos
		6. Manter campo 'Password' vazio
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro 'Password can't be blank.'
		
		Status: Aprovado
		
	TC-006 - Registrar com Campo 'Email Address' em Formato Inválido
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Preencher campo 'First Name' com dados válidos
		4. Preencher campo 'Last Name' com dados válidos
		5. Preencher campo 'Email Address' com dados inválidos (Por exemplo: test.com)
		6. Preencher campo 'Password' com dados válidos
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro informando que o endereço de Email está inválido
			
		Status: Aprovado
		
	TC-007 - Registrar com Todos os Campos Vazios
	
		Prioridade: Alta
		
		Passos - 
		1. Acessar https://sauce-demo.myshopify.com/
		2. Clicar no botão 'Sign up' localizado no header
		3. Manter campo 'First Name' vazio
		4. Manter campo 'Last Name' vazio
		5. Manter campo 'Email Address' vazio
		6. Manter campo 'Password' vazio
		7. Clicar no botão 'Create'
		
		Resultado esperado - 
			Registro não concluído e exibição de mensagem de erro informando que os campos são obrigatórios:
			"- First name can't be blank.
			 - Last name can't be blank.
			 - Email can't be blank.
			 - Password can't be blank."
			
		Status: Falhou
		
		Resultado obtido -
			Registro não concluído e foram exibidas apenas as seguintes mensagens de erro:
			"- Email can't be blank.
			 - Password can't be blank."
			 
		- Fim -
-\\-
	Registration Test Cases - EN-US
-\\-

	Criteria		- User should be able to create an account using valid data
					- Required fields should not accept empty data
					- Email field should accept only valid Email address
	URL: https://sauce-demo.myshopify.com/
	Preconditions - N/A
	Test Data 		- Email: jl.genericutesting@gmail.com
					- Password: test123
					- First Name: João
					- Last Name: Test
					
		- Start -
		
	TC-001 - User Successfully Registers
	
		priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on 'Sign up' button in the header
		3. Fill the 'First Name' field with valid data
		4. Fill the 'Last Name' field with valid data
		5. Fill the 'Email Address' field with valid Email address
		6. Fill the 'Password' field with valid data
		7. Click on the 'Create' button
		
		Expected Result - 
			User is successfully registered and redirected to home page with their account logged in
		
		Status: Passed
		
		
	TC-002 - User Registers With The 'First Name' Field Empty
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Keep the 'First Name' field empty
		4. Fill the 'Last Name' field with valid data
		5. Fill the 'Email Address' with valid Email Address
		6. Fill the 'Password' field with valid data
		7. Click on the 'Create' Button
		
		Expected Result - 
			Registration should fail, and the error message 'First Name can't be blank.' should be displayed
		
		Status: Passed
		
	TC-003 - User Registers With The 'Last Name' Field Empty
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Fill the 'First Name' field with valid data
		4. Keep the 'Last Name' field empty
		5. Fill the 'Email Address' field with valid Email Address
		6. Fill the 'Password' field with valid data
		7. Click on the 'Create' button
		
		Expected Result - 
			Registration should fail, and the error message 'Last name can't be blank.' should be displayed
		
		Status: Passed
		
	TC-004 - User Registers With The 'Email Address' Field Empty
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Fill the 'First Name' field with valid data
		4. Fill the 'Last Name' field with valid data
		5. Keep the 'Email Address' field empty
		6. Fill the 'Password' field with valid data
		7. Click on the 'Create' button
		
		Expected Result - 
			Registration should fail, and the error message 'Email can't be blank.' should be displayed
		
		Status: Passed
		
	TC-005 - User Registers With The 'Password' Field Empty
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Fill the 'First Name' field with valid data
		4. Fill the 'Last Name' field with valid data
		5. Fill the 'Email Address' field with valid data
		6. Keep the 'Password' field empty
		7. Click on the 'Create' button
		
		Expected Result - 
			Registration should fail, and the error message 'Password can't be blank.' should be displayed
		
		Status: Passed
		
	TC-006 - User Registers With The 'Email Address' Field in a Invalid Format
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Fill the 'First Name' field with valid data
		4. Fill the 'Last Name' field with valid data
		5. Fill the 'Email Address' field with invalid format (e.g: test.com)
		6. Fill the 'Password' field with valid data
		7. Click on the 'Create' button
		
		Expected Result - 
			Registration should fail, and an error messagem for invalid Email Address should be displayed
			
		Status: Passed
		
	TC-007 - User Registers With All Fields Empty
	
		Priority: High
		
		Steps - 
		1. Navigate to https://sauce-demo.myshopify.com/
		2. Click on the 'Sign up' button in the header
		3. Keep the 'First Name' field empty
		4. Keep the 'Last Name' field empty
		5. Keep the 'Email Address' field empty
		6. Keep the 'Password' field empty
		7. Click on the 'Create' button
		
		Expected Result - 
			Registration should fail, and the error messages should be displayed:
			"- First name can't be blank.
			 - Last name can't be blank.
			 - Email can't be blank.
			 - Password can't be blank."
			
		Status: Failed
		
		Actual Result -
			Registration failed, and the error messages displayed was only:
			"- Email can't be blank.
			 - Password can't be blank."
			 
		- End - 
		
-\\-
