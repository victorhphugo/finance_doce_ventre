# 💰 Finance Doce Ventre

Sistema de controle financeiro feito para pequenos negócios ,autonomos, e-comerce entre outros. Este projeto foi desenvolvido com foco em analise financeira ,controle de gastos, relatorios , dashboards e por fim integrando ao chatgpt para analisar os relatorios com sugestões personalizadas por uma inteligencia artificial. 

---

## 🚀 Tecnologias

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Vercel](https://vercel.com/) para deploy

---

## 📦 Funcionalidades

- Cadastro de entradas (receitas) e saídas (despesas)
- Visualização e acompanhamento de fluxo de caixa
- Autenticação de usuário
- Dashboard com dados atualizados
- Interface responsiva com componentes otimizados
- em andamento (dashboard) , (integração api gpt).

   
---

## 🛠️ Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/victorhphugo/finance_doce_ventre.git

# Entre na pasta do projeto
cd finance_doce_ventre

# Instale as dependências
npm install

# Crie um arquivo .env e configure o banco de dados
# Exemplo de variável:
# DATABASE_URL="postgresql://usuario:senha@localhost:5432/nome_do_banco"

# Execute as migrações
npx prisma migrate dev

# Rode o projeto
npm run dev
```
## 🗂️ Estrutura de Pastas

- /app         -> Páginas e rotas
- /components  -> Componentes reutilizáveis
- /prisma      -> Schema e migrations do banco de dados
- /public      -> Arquivos estáticos
