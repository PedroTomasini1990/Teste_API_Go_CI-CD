# API Go Gin - Estrutura e Automação

Este repositório contém uma API em Go, desenvolvida com o framework Gin, para gerenciar informações de alunos. O projeto abrange operações básicas como criação, leitura, atualização e exclusão de registros.

## Estrutura do Código

- **`main.go`**: Arquivo principal que inicia o servidor Gin e define as rotas da API.
- **`controllers/`**: Diretório contendo controladores para cada rota da API.
- **`models/`**: Contém os modelos de dados, como o modelo de aluno.
- **`database/`**: Configuração e conexão com o banco de dados.

## Testes Unitários

Os testes unitários são fundamentais para garantir a integridade e o desempenho da aplicação. Eles estão localizados no arquivo `main_test.go` e são executados automaticamente usando GitHub Actions em cada push para a branch 'main' e em cada pull request para a 'main'.

## Automação com GitHub Actions

O GitHub Actions é utilizado para automatizar o processo de teste e construção da aplicação. Duas jobs foram configuradas:

1. **Teste:**
   - Executa os testes unitários em diversas versões do Go e ambientes.
   - Configura um banco de dados local usando Docker Compose para os testes.

2. **Construção:**
   - Realiza a construção da aplicação.

Essas ações garantem que a aplicação seja testada automaticamente em diferentes ambientes e versões do Go, proporcionando confiabilidade ao código.

## Como Contribuir

Sinta-se à vontade para contribuir, relatar problemas ou sugerir melhorias. Seu feedback é essencial para o aprimoramento contínuo do projeto.

## Licença

Este projeto é distribuído sob a [Licença MIT](LICENSE), conferindo a liberdade para compartilhar e modificar o código conforme necessário.
