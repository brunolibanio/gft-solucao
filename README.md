# gft-solucao
# Controle de Fluxo de Caixa

## Descrição

Sistema para controle de fluxo de caixa diário e geração de relatórios consolidados.

## Tecnologias Utilizadas

- **Frontend**: React (hospedado em AWS Amplify ou S3 + CloudFront)
- **Backend**: AWS Lambda (Node.js) e API Gateway
- **Banco de Dados**: Amazon DynamoDB
- **Relatórios**: Amazon QuickSight e S3 para armazenamento

## Instalação e Execução Local

### Frontend

1. Navegue para a pasta `frontend`:
    ```bash
    cd frontend
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Execute a aplicação:
    ```bash
    npm start
    ```

### Backend

1. Navegue para a pasta `backend/lambda-functions/create-transaction`:
    ```bash
    cd backend/lambda-functions/create-transaction
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```

## Testes

- Teste o frontend localmente acessando `http://localhost:3000`.
- Teste as funções Lambda localmente usando ferramentas como AWS SAM CLI ou no ambiente AWS.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações: `git checkout -b feature/nova-feature`.
3. Faça o commit das suas alterações: `git commit -am 'Adiciona nova feature'`.
4. Envie a branch para o repositório remoto: `git push origin feature/nova-feature`.
5. Crie um pull request.

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.
