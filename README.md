### **README.md**

# To-Do List API

Este projeto é o scaffolding inicial de uma API para gestão de tarefas (To-Do List). Ele fornece a estrutura básica para o desenvolvimento de uma aplicação backend, utilizando Node.js, Express e Swagger para documentação.

---

## Como rodar o projeto

### Pré-requisitos
- Node.js (v16 ou superior)
- npm ou yarn
- Git (opcional)

### Passos para execução

1. Clone o repositório:
   
   ```bash
   git clone https://github.com/seu-usuario/to-do-list-api.git
   ```

2. Acesse a pasta do projeto:
   
   ```bash
   cd to-do-list-api
   ```
   
3. Instale as dependências:
   
   ```bash
   npm install
   ```

4. Configure o arquivo `.env`:
   - Renomeie o arquivo `.env.example` para `.env`.
   - Defina a variável `PORT` no arquivo `.env` (opcional, o padrão é 3000).

5. Inicie o servidor em modo de desenvolvimento:
   
   ```bash
   npm run dev
   ```

6. Acesse a API:
   - A rota principal estará disponível em: `http://localhost:3000/api/`.
   - A documentação interativa (Swagger) estará disponível em: `http://localhost:3000/api-docs/`.

## Estrutura do Projeto

to-do-list-api/
├── src/
│   ├── config/                  # Configurações do projeto
│   ├── controllers/             # Controladores da API
│   ├── models/                  # Modelos de dados (Tarefas)
│   ├── routes/                  # Definição das rotas da API
│   ├── middlewares/             # Middlewares customizados
│   ├── docs/                    # Configuração do Swagger
│   └── index.js                 # Ponto de entrada da aplicação
├── .env                         # Variáveis de ambiente
├── .env.example                 # Exemplo de variáveis de ambiente
├── .gitignore                   # Arquivos ignorados pelo Git
├── .eslintrc.json               # Configuração do ESLint
├── .prettierrc                  # Configuração do Prettier
├── package.json                 # Dependências e scripts do projeto
└── README.md                    # Documentação do projeto


## Como contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se tiver dúvidas ou sugestões, entre em contato:

- **Nome**: [Isabella Dreher Emerichs Da Rosa]
- **E-mail**: [isabella.emerichs@gmail.com]
- **GitHub**: [[Bellapy](https://github.com/Bellapy)]

### **Testar a Aplicação**
   - Acesse `http://localhost:3000/api/` para ver a mensagem de boas-vindas.
   - Acesse `http://localhost:3000/api-docs/` para visualizar a documentação Swagger.