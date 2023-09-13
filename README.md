# UPLOAD-AI-API

Uma API para o projeto **UPLOAD.AI** que utiliza tecnologias modernas para gerenciar uploads e processamento de vídeos com suporte a transcrição de áudio.

## Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Prisma](https://prisma.io/)
- [SQLite](https://www.sqlite.org/)
- [TypeScript](https://www.typescriptlang.org/)

## Pré-requisitos

- Node.js e npm instalados em sua máquina.
- Um ambiente de desenvolvimento configurado para TypeScript.

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/upload-ai-api.git
   cd upload-ai-api

Execute as migrações do Prisma para criar as tabelas no banco de dados SQLite:

```
npx prisma migrate dev
```

Inicie o servidor de desenvolvimento:

```
npm run dev
```
### Configuração do Banco de Dados

Certifique-se de configurar a conexão com o banco de dados SQLite no arquivo .env. Você pode copiar o arquivo .env.example e ajustar as configurações conforme necessário.

```
DATABASE_URL="file:./dev.db"
```

### Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests para melhorar este projeto.

### Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.