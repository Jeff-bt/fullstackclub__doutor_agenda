# Doutor Agenda 🏥

Um sistema moderno de agendamento médico desenvolvido com as mais recentes tecnologias web. O Doutor Agenda oferece uma interface intuitiva para gerenciamento de consultas, pacientes e profissionais de saúde.

## 🚀 Tecnologias Utilizadas

- **Frontend:**

  - Next.js 15
  - React 19
  - TypeScript
  - Tailwind CSS
  - Shadcn (Componentes acessíveis)
  - React Query (Gerenciamento de estado e cache)
  - React Hook Form (Formulários)
  - Zod (Validação de dados)

- **Backend:**

  - Next.js API Routes
  - Drizzle ORM
  - PostgreSQL
  - Better-auth (authenticação)
  - Stripe (Pagamentos)

- **Ferramentas de Desenvolvimento:**
  - ESLint
  - Prettier
  - TypeScript
  - Drizzle Kit

## 📋 Pré-requisitos

- Node.js (versão LTS recomendada)
- PostgreSQL
- Conta no Stripe (para funcionalidades de pagamento)

## 🔧 Configuração do Ambiente

1. Clone o repositório:

```bash
git clone [URL_DO_REPOSITÓRIO]
cd doutor-agenda
```

2. Instale as dependências:

```bash
npm install
```

3. Configure as variáveis de ambiente:
   Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:

```bash
cp .env.example .env.local
```

4. Execute as migrações do banco de dados:

```bash
npm run db:migrate
```

## 🚀 Executando o Projeto

### Desenvolvimento

```bash
npm run dev
```

A aplicação estará disponível em `http://localhost:3000`

### Produção

```bash
npm run build
npm start
```

## 🛠️ Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria a build de produção
- `npm start` - Inicia o servidor de produção
- `npm run lint` - Executa a verificação de código
- `npm run db:migrate` - Executa as migrações do banco de dados

## 📦 Estrutura do Projeto

```
src/
├── actions/     # Server actions
├── app/         # Rotas e páginas
├── components/  # Componentes React
├── db/          # Configuração do banco de dados
├── helpers/     # Funções auxiliares
├── hooks/       # Custom hooks
├── lib/         # Configurações e utilitários
├── providers/   # Providers React
└── data/        # Dados e tipos
```

## 🔐 Funcionalidades

- Autenticação de usuários
- Agendamento de consultas
- Gerenciamento de pacientes
- Dashboard administrativo
- Integração com pagamentos via Stripe

## 📝 Licença

Este projeto esta sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
