🚀 **Rocketlog — API de Controle de Entregas**

Uma API enxuta e organizada para gerenciar entregas, criada com foco em boas práticas, arquitetura limpa e consolidação de fundamentos no back-end.

Este projeto faz parte da minha jornada para me tornar um desenvolvedor fullstack e serve como laboratório real para aprimorar minhas habilidades.


**🧰 Tecnologias Utilizadas**


Node.js + Express — estrutura leve e eficiente para criação de APIs.

TypeScript — segurança e previsibilidade com tipagem estática.

Prisma ORM — modelagem, migrações e acesso ao PostgreSQL com produtividade.

PostgreSQL — banco de dados relacional robusto.

JWT — autenticação baseada em token.

Jest + Supertest — testes unitários e de integração.

**📁 Estrutura do Projeto**
```
Rocketlog/
├── docker-compose.yml
├── jest.config.js
├── package.json
├── tsconfig.json
├── prisma/
│   ├── schema.prisma
│   └── migrations/
└── src/
    ├── app.ts
    ├── env.ts
    ├── server.ts
    ├── configs/
    ├── controllers/
    ├── database/
    ├── middlewares/
    ├── routes/
    ├── tests/
    ├── types/
    └── utils/
```
**⚙️ Configuração**

1.Duplique o arquivo .env-example e renomeie para .env.

2.Preencha as variáveis necessárias:

```
DATABASE_URL

JWT_SECRET

PORT
```
Se quiser subir um PostgreSQL com Docker, basta usar o serviço já configurado:
```
docker compose up -d
```

**📦 Instalação**
```
npm install
```

**🗄️ Banco de Dados (Prisma)**

```
Gere o client do Prisma:

npx prisma generate
Aplique as migrações:

bash
Copiar código
npx prisma migrate deploy
```

**▶️ Execução**

Ambiente de desenvolvimento:

```
npm run dev
```

Build + produção:

```
npm run build
npm start
```

**🧪 Testes**
```
npm run test:dev
```

**📚 Sobre o Projeto**

Este código é aberto para estudo, referência e experimentação.
Sinta-se livre para explorar, abrir issues, sugerir melhorias ou utilizá-lo como base para outros projetos.
