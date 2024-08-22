# Urban Routes - Testes de API e Verificação de Funcionalidades


Este repositório contém o projeto de testes de API do aplicativo Urban Routes.

## Descrição do Projeto

O Urban Routes é um aplicativo que auxilia usuários na criação de rotas, calculando o tempo e o custo da viagem para diferentes meios de transporte. Nesta sprint, o foco foi testar a nova funcionalidade de compartilhamento de carros e o serviço de entrega Order and Go implementados no backend do Urban.Grocers.

## Objetivo do Projeto

O objetivo deste projeto foi testar a API da nova funcionalidade adicionada ao Urban.Grocers, garantindo que os endpoints funcionem conforme o esperado e que todos os requisitos do backend sejam atendidos.

## Habilidades Testadas

- HTTP: Compreensão e aplicação de métodos HTTP na comunicação com a API.
- Teste de API: Criação e execução de testes para validar as funcionalidades da API.
- Postman: Utilização do Postman para testar e validar os endpoints da API.

## Endpoints Testados

### Adicionar Produtos a um Kit  
- Endpoint: POST /api/v1/kits/{id}/products
- Descrição: Adiciona produtos a um kit específico. O endpoint retorna um erro 400 Bad Request quando o número total de produtos excede 30.

### Verificar Serviço de Entrega - Order and Go
- Endpoint: POST /order-and-go/v1/delivery
- Descrição: Verifica a disponibilidade do serviço de entrega "Order and Go" e calcula o custo da entrega.

## Estrutura dos Arquivos

Planilha do Excel: Contém o checklist de testes, casos de teste, resultados e link com acesso aos relatórios de bug no Jira.

## Conclusão

Os testes realizados no projeto mostraram que, embora a nova funcionalidade do Urban.Grocers seja promissora, foram encontrados bugs críticos que precisam ser resolvidos antes de sua implementação em produção. A validação foi bem-sucedida, mas melhorias são necessárias para garantir a robustez da API e a qualidade da experiência do usuário.
