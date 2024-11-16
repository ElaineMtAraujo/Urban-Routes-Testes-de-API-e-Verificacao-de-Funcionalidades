# 🚀 Urban Routes - Testes de API e Verificação de Funcionalidades


Este repositório contém o projeto de testes de API do aplicativo Urban Routes.

## 📱 Descrição do Projeto
Este repositório contém o projeto de Testes de API do aplicativo Urban Routes.

O Urban Routes é um aplicativo que auxilia usuários na criação de rotas, calculando o tempo e o custo da viagem para diferentes meios de transporte. Nesta sprint, o foco foi testar a nova funcionalidade de compartilhamento de carros e o serviço de entrega Order and Go implementados no backend do Urban.Grocers.

## 🎯 Objetivo do Projeto

O objetivo deste projeto foi testar a API da nova funcionalidade adicionada ao Urban.Grocers, garantindo que os endpoints funcionem conforme o esperado e que todos os requisitos do backend sejam atendidos.

## 🏆 Resultados Esperados

Os testes realizados no projeto mostraram que, embora a nova funcionalidade do Urban.Grocers seja promissora, foram encontrados bugs críticos que precisam ser resolvidos antes de sua implementação em produção. A validação foi bem-sucedida, mas melhorias são necessárias para garantir a robustez da API e a qualidade da experiência do usuário.

Exemplo de Resultados: 

- Endpoint: Adicionar Produtos a um Kit
- Erro encontrado: 400 Bad Request quando o número de produtos excede 30.
- Resultado esperado: O endpoint deve retornar erro somente se o número de produtos for maior que 30.
- Solução: O endpoint foi ajustado para validar corretamente o número de produtos.

📊 Captura de Tela: 

<img width="1106" alt="Screenshot 2024-11-16 at 15 40 34" src="https://github.com/user-attachments/assets/8e0c98bd-a85c-42f6-8458-1dfdaad9ef08">

## 📂 Estrutura dos Arquivos

📄 Planilha do Excel

Contém o checklist de testes, casos de teste, resultados e link com acesso aos relatórios de bug no Jira.

##  \🔍 Habilidades Testadas

Durante a realização deste projeto, foram avaliadas as seguintes competências:

🌐 HTTP: Compreensão e aplicação de métodos HTTP na comunicação com a API.

🔧 Teste de API: Criação e execução de testes para validar as funcionalidades da API.

💻 Postman: Utilização do Postman para testar e validar os endpoints da API.

🔌 Endpoints Testados

Adicionar Produtos a um Kit:
-Endpoint: POST /api/v1/kits/{id}/products
-Descrição: Adiciona produtos a um kit específico. O endpoint retorna um erro 400 Bad Request quando o número total de produtos excede 30.
-Verificar Serviço de Entrega - Order and Go
-Endpoint: POST /order-and-go/v1/delivery
-Descrição: Verifica a disponibilidade do serviço de entrega "Order and Go" e calcula o custo da entrega.

## 💡 Possíveis Melhorias

🔹 Validar melhor a entrada de dados, garantindo que a API não retorne erros inesperados.
🔹 Implementar testes de carga para garantir que a API possa lidar com um grande número de requisições.
🔹 Documentar mais detalhadamente os erros retornados pela API, ajudando na resolução de problemas rapidamente.

## 📋 Como Utilizar

1️⃣ Clone este repositório:
git clone https://github.com/ElaineMtAraujo/Urban-Routes-Testes-de-API-e-Verificacao-de-Funcionalidades.git

2️⃣ Use o Postman para testar os endpoints descritos acima e validar suas funcionalidades.

3️⃣ Consulte a planilha do Excel para ver o checklist de testes e resultados detalhados.

## 🤝 Contribuindo

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:

1.Faça um fork deste repositório.

2.Crie uma branch para sua contribuição: git checkout -b minha-contribuicao

3.Envie um pull request explicando suas alterações.

## 🕒 Atualizações Recentes

[16/11/2024]: Atualização do README com novas seções, incluindo Endpoints Testados e Possíveis Melhorias.

## ⚠️ Observações
Os testes realizados ajudaram a identificar pontos críticos na funcionalidade da API. Para garantir a qualidade da experiência do usuário, melhorias adicionais são necessárias antes da implementação em produção.
