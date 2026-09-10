# Test Plan — Sauce Demo

## 1. Objetivo
  O Objetivo desse plano de teste é definir a abordagem para a aplicação web Saude Demo, verificando se suas principais funcionalidades apresentam o comportamento esperado.
## 2. Scope

### In Scope
  As seguintes funcionalidades serão testadas:
  - Registro de usuário
  - Login
  - Listagem de produtos
  - Detalhes dos produtos
  - Carrinho de compras
  - Processo de Checkout
  - Logout

### Out of Scope
  As seguintes áreas não fazem parte desse projeto:
  - Teste de Performance
  - Teste de segurança
  - Teste de API
  - Teste de DB
  - Teste do código-fonte
  - Teste automatizado

## 3. Test Strategy
  Os testes serão executados manualmente, com base no comportamento esperado das funcionalidades listadas.
  A abordagem para os testes incluirá:
  - Testes Funcionais
  - Testes Positivos
  - Testes Negativos
  - Testes exploratórios
  - Testes de limite (Edge) (Onde aplicável)

  Os defeitos encontrados durante a execução dos testes serão registrados individualmente, contendo informações de passos para reprodução, resultado esperado, resultado obtido, severidade, prioridade e evidências (Onde aplicável). <br>
  <br>
  Defeitos, Test Cases e Relatórios serão disponibilizados em linguagem original PT-BR e posteriormente traduzidas para Inglês
## 4. Test Types

  <h3>Teste Funcional</h3>
    - Verifica se as funcionalidades apresentam o comportamento esperado quando fornecido dados válidos. <br>

  <h3>Teste Negativo</h3>
    - Verifica se as funcionalidades apresentam o comportamento esperado quando fornecido dados inválidos. <br>

  <h3>Teste Explorátorio</h3>
    - Testa a aplicação sem seguir um script de passos ou ordens definidas. O mais próximo de um usuário comum fazendo uso da aplicação. <br>

  <h3>Teste de Limite (Edge) </h3>
  - Verifica se as funcionalidades apresentam o comportamento esperando quando fornecido dados que fogem os de uso comum de um usuário. Busca padrões que um usuário comum dificilmente encontraria.

## 5. Test Environment
- Aplicação: Sauce Demo
- URL: https://sauce-demo.myshopify.com/
- OS: Windows 10 Pro
- Navegador: Google Chrome
- Versão do Navegador: 153.0.8010.37
- Tipo de Teste: Teste Manual

## 6. Test Data

Os seguintes dados serão usados durante os testes<br>

Usuário válido:<br>
- E-mail: jl.genericutesting@gmail.com
- Password: test123
<br>
Dados inválidos:<br>
Serão usados dados inválidos ou incompletos para a validação de cenários negativos durante os testes:

- Usuário inválido
- Senha inválida
- Campos obrigatórios vazios
- Dados inválidos durante o processo de Checkout


## 7. Entry Criteria
Os testes poderão ser iniciados quando:
- A aplicação estiver disponível
- As principais funcionalidades estiverem disponíveis
## 8. Exit Criteria
Os testes serão considerados concluídos quando:<br>

- Todos os casos de teste planejados tiverem sido executados
- Os resultados dos testes tiverem sido documentados
- Os defeitos identificados tiverem sido registrados
- O teste exploratório tiver sido realizado
- O relatório final de testes tiver sido elaborado

## 9. Risks
Os seguintes riscos podem afetar a execução dos testes:<br>

- Alterações na aplicação durante o período de testes
- Indisponibilidade temporária da aplicação
- Defeitos não identificados dentro do escopo definido

## 10. Deliverables
Os seguintes artefatos serão produzidos neste projeto:<br>

- Test Plan
- Test Cases
- Registro da execução dos testes
- Relatório da execução dos teste exploratório
- Bug reports
- Evidência dos testes
- Relatório Final dos Testes
